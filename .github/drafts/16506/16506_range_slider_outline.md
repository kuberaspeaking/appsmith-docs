*** Range Slider ***

The Range Slider widget allows users to choose a range of values from numerical data.

< TODO: NEED VIDEO DEMO >

---
# Usage
- Example use case: Search filtering (i.e. Min/ Max price)

---

# Properties

Properties allow you to edit the widget, connect it with other widgets and customize the user actions.

## Widget Properties

These properties allow you to edit the Range Slider widget. The following table lists all the widget's unique properties; if you do not see a certain widget property here, it may be listed under [Common Widget Properties]().

| **Property** | **Description** |
|--------------|-----------------|
| **Min Value** | The starting/smallest possible value of the slider. The value may be negative and/or include decimals, however it must always be less than the **Max Value**. _(number)_ |
| **Max Value** | The ending/largest possible value of the slider. The value may be negative and/or include decimals, however it must always be greater than the **Min Value**. _(number)_ |
| **Step Size** | The increment by which the user can adjust the slider's value. This increment must be at least 0.1, and cannot be less than the **Min Value** or greater than the **Max Value**. _(number)_ |
| **Min Range** |  |
| **Default Start Value** |  |
| **Marks** | An _array of objects_ with keys `value` and `label` which define where reference labels should appear below the widget's slider. These labels can be shown or hidden with the **Show Marks** property toggle. |
| **Tooltip Always On** | Hovering over the slider with the mouse cursor shows the slider's selected value in a tooltip; enabling this setting will force the tooltip to always be visible, regardless of the cursor's location. _(bool)_ |

### Min Value / Max Value

### Step Size

### Min Range

### Default Start Value

### Marks

### Tooltip Always On

## Binding Properties

These properties allow you to bind your Range Slider Checkbox widget with any other widget in queries or JS objects. The following table lists all the binding properties.

| **Binding Property** | **Description** |
|----------------------|-----------------|
| **startValue** | Represents the beginning value of the user's selected range. _(number)_ |
| **endValue** | Represents the ending value of the user's selected range. _(number)_ |

### startValue / endValue

## Events

You can define functions that will be called when these events are triggered in the widget.

| **Event** | **Description** |
|-----------|-----------------|
| **onStartValueChange** | Sets an an action to take place when the user changes the range's start value. Can be set from the GUI list of common actions (See a list of [supported actions](https://docs.appsmith.com/reference/appsmith-framework/widget-actions)), or you can define a custom JavaScript function to call instead. |
| **onEndValueChange** | Sets an an action to take place when the user changes the range's end value. Can be set from the GUI list of common actions (See a list of [supported actions](https://docs.appsmith.com/reference/appsmith-framework/widget-actions)), or you can define a custom JavaScript function to call instead. |

### onStartValueChange / onEndValueChange

## Styles

| **Style** | **Description** |
|-----------|-----------------|
| **Size** | Sets the size of the widget on the canvas; choose from **S** (Small/4px), **M** (Medium/6px), or **L** (Large/8px). |
| **Color** | Sets the fill color of the slider element. Accepts valid CSS [`color`](https://developer.mozilla.org/en-US/docs/Web/CSS/color) values. |

### Size

### Color

