# Checkboxes

There are two types of checboxes: **Single-select** \(without a label\) in cases where they represent an enable/disable action; and **Multi-select** when there are multiple choices, and more than one option can be selected. Checkboxes have up to 6 states, including: default, on-hover, on-focus, disabled, hint and error. All checkboxes have width and height of 24px

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines

* Consider using a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) if there are several \(6+\) choices; or in cases the form is long, or space is limited.
* Checkbox Multi-select are preferable over a[ _Dropdown Multi-select_](https://www.gitbook.com/book/milosmirkovic89/back-office/edit#) when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a multi-select.
* A checkbox does not apply a setting at an instant. Instead, it’s accompanied by a submit button and takes effect after the user presses it.
* If the instantaneous action is required, then use the Switches instead. Switches always indicate whether a setting is on or off, and the action is instant, does not require a submit button press.

##### Spacing guidelines

![](/assets/atoms/checkboxes-spacing.png)

### Single-select

Single-select checkboxes are standalone and they are used as an enable/disable action in forms.

![](/assets/atoms/checkboxes-single-select-states.png)

