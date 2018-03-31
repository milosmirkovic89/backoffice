# Radio buttons

Radio buttons are mostly used when there are multiple choices, but only one option can be selected. Radio buttons can be displayed as a **Stand-alone** and as a **Sub-option**. They have up to 5 states, including: default, on-hover, on-focus, disabled and hint.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines {#general-guidelines}

* Radio buttons are ideal for simple either/or choices, or when there are only a couple/few choices.
* Consider using a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) if there are 6+ choices; or in cases the form is long, or space is limited.
* Radio buttons are preferable over a [_Dropdown Multi-select_](//atoms/dropdowns.html#multi-select) when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a select.
* A radio button can never be used singularly \(e.g. for a yes/no or opt-in/out data capture\), as it can only be selected, not un-selected. Therefore, a minimum of two options must be presented to use radio buttons. Use a [_Checkbox Single-select_](//atoms/checkboxes.html#single-select) if there is only one option.

#### Spacing guidelines

* The width size of the radio buttons is 20px.
* The height size of the radio buttons is 20px.
* The margin between radio buttons is 8px.

![](/assets/atoms/radio-buttons-states.png)

```
/* Default base */
background: $S100;
width: 20px;
height: 20px;
border: 1px solid $S500;
border-radius: 100%;

/* Default dot */
background: $G300;
width: 10px;
height: 10px;
border-radius: 100%;
margin: 5px 0 0 5px

/* Default label */
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B300;

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
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B300;
```

---

### Stand-alone

* The first radio button in a Stand-alone group has a margin top of 10px.
* The last radio button in a Stand-alone group has a margin bottom of 10px.

![](/assets/atoms/radio-buttons-stand-alone.png)

### Sub-option

* The top margin above the first Radio button in a Sub-option group is 8px.
* The bottom margin below the last Radio button in a Sub-option group is 8px.
* There is an "L" indicator before each Sub-option Radio button \(height: 8px, width: 12px, border: 2px\).

![](/assets/atoms/radio-buttons-sub-options.png)

```
/* "L" Indicator */
color: $S300;
```



