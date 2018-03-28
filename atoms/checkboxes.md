# Checkboxes

There are two types of checkboxes: **Single-select** \(without a label\) in cases where they represent an enable/disable action; and **Multi-select** when there are multiple choices, and more than one option can be selected. Checkboxes have up to 6 states, including: default, on-hover, on-focus, disabled, hint and error.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines

* Consider using a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) if there are 6+ choices; or in cases the form is long, or space is limited.
* Checkbox Multi-select are preferable over a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select).
* A checkbox does not apply a setting at an instant. Instead, it’s accompanied by a submit button and takes effect after the user presses it.
* If the instantaneous action is required, then use the [_Toggles_](/atoms/toggles.md) instead. Switches always indicate whether a setting is on or off, and the action is instant, does not require a submit button press.

### Single-select

Single-select checkboxes are standalone and they are used as an enable/disable action in [Forms](/organisms/forms.md) but require a submit button press in order for action to take the effect.

* The width size of a Single-select is 24px.
* The height size of a Single-select is 24px.
* Single-select has a margin top and bottom of 8px.

![](/assets/atoms/checkboxes-single-select-states.png)

```
/* Single-select checkbox/ default */
width: 24px;
height: 24px;
background: $S100;
border: 1px solid $S500;
border-radius: 3px;
margin: 8px 0 8px 0;

/* Single-select checkbox / on hover */
box-shadow: 1px 1px 4px 0 $S300;

/* Single-select checkbox / on focus */
border: 1px solid $G200;
box-shadow: 1px 1px 4px 0 $G200;

/* Single-select checkbox / disabled */
opacity: 50%;
```

---

### Multi-select

Multi-select checkboxes are used when there are multiple choices, and more than one option can be selected. Like Single-select checkboxes, these ones require a submit button press as well.

* The width size of a Multi-select is 24px.
* The height size of a Multi-select is 24px.
* The margin between Multi-selects is 8px.
* The first Multi-select in a group has a margin top of 8px.
* The last Multi-select in a group has a margin bottom of 8px.
* There is a margin of 8px between a checkbox and a checkbox label.
* Only first letter of the checkbox label should be capitalized.

![](/assets/atoms/checkboxes-multi-select-states.png)

```
/* Multi-select checkbox / default */
width: 24px;
height: 24px;
background: $S100;
border: 1px solid $S500;
border-radius: 3px;
margin: 8px 8px 8px 0;

/* Multi-select label / default */
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B300;

/* Multi-select checkbox / on hover */
box-shadow: 1px 1px 4px 0 $S300;

/* Multi-select label / on hover */
color: $S500;

/* Multi-select checkbox / on focus */
border: 1px solid $G200;
box-shadow: 1px 1px 4px 0 $G200;

/* Multi-select label / on focus */
color: $B100;

/* Multi-select checkbox / disabled */
opacity: 50%;

/* Multi-select label / disabled */
opacity: 50%;

/* Multi-select checkbox / error */
border: 1px solid $G300;

/* Multi-select error message */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $R300;

/* Multi-select hint message */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B300;
```



