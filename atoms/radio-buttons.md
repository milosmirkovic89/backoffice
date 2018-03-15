# Radio buttons

Radio buttons are mostly used when there are multiple choices, but only one option can be selected. They have up to 5 states, including: default, on-hover, on-focus, disabled and hint.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines {#general-guidelines}

* Radio buttons are ideal for simple either/or choices, or when there are only a couple/few choices.
* Consider using a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) if there are 6+ choices; or in cases the form is long, or space is limited.
* Radio buttons are preferable over a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a select.
* A radio button can never be used singularly \(e.g. for a yes/no or opt-in/out data capture\), as it can only be selected, not un-selected. Therefore, a minimum of two options must be presented to use radio buttons. Use a [_Checkbox Single-select_](//atoms/checkboxes.html#single-select) if there is only one option.

#### Spacing guidelines

* The width and height of the radio buttons are always 20px.
* Radio buttons have a top and bottom margin of 10px and a right margin of 8px.

![](/assets/atoms/radio-buttons-states.png)

```
/* Default base */
background: $S100;
width: 20px;
height: 20px;
border: 1px solid $S500;
border-radius: 100%;
margin: 10px 8px 10px 0;

/* Default label */
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B300;

/* Default dot */
background: $G300;
width: 10px;
height: 10px;
border-radius: 100%;
margin: 5px 0 0 5px

/* On hover base */
box-shadow: 1px 1px 4px 0 $S300;

/* On hover label */
color: $S500;

/* On focus base */
border: 1px solid $G200;
box-shadow: 1px 1px 4px 0 $G200;

/* On focus label */
color: $S500;

/* Disabled */
opacity: 50%;

/* Hint message */
margin-top: 8px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B300;
```



