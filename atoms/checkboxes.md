# Checkboxes

There are two types of checboxes: **Single-select** \(without a label\) in cases where they represent an enable/disable action; and **Multi-select** when there are multiple choices, and more than one option can be selected. Checkboxes have up to 6 states, including: default, on-hover, on-focus, disabled, hint and error. All checkboxes have width and height of 24px

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines

* Consider using a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) if there are 6+ choices; or in cases the form is long, or space is limited.
* Checkbox Multi-select are preferable over a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select).
* A checkbox does not apply a setting at an instant. Instead, it’s accompanied by a submit button and takes effect after the user presses it.
* If the instantaneous action is required, then use the [_Switches_](#) instead. Switches always indicate whether a setting is on or off, and the action is instant, does not require a submit button press.

#### Spacing guidelines

* The width and height of the checkbox base is always 24px.
* Checkboxes have a top, right and bottom margin of 8px.

![](/assets/atoms/checkboxes-spacing.png)

### Single-select

Single-select checkboxes are standalone and they are used as an enable/disable action in forms but require a submit button press in order for action to take the effect.

![](/assets/atoms/checkboxes-single-select-states.png)

```
/* Default */
background: $S100;
width: 24px;
height: 24px;
border: 1px solid $S400;
border-radius: 3px;
margin: 8px 8px 8px 0

/* On hover */
box-shadow: 1px 1px 4px 0 #E0E0E0;

/* On focus */
border: 1px solid $G200;

/* Disabled */
opacity: 50%;
```

---

### Multi-select

Multi-select checkboxes are used when there are multiple choices, and more than one option can be selected. Like Single-select checkboxes, these ones require a submit button press as well.

![](/assets/atoms/checkboxes-multi-select-states.png)

```
/* Differences compared to the Single-select */

/* Default */
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B200;

/* On hover */
color: $B300;

/* On focus */
color: $B300;

/* Disabled */
opacity: 50%;

/* Error */
border: 1px solid $G300;

/* Error message */
margin-top: 8px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $R300;

/* Hint message */
margin-top: 8px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B300;
```



