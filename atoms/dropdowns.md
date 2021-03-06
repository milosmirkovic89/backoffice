# Dropdowns

Dropdown list menus are categorized into two main groups: **Single-select** and **Multi-select** dropdowns. Both of them have up to 7 states, including default, on-hover, on-focus, filled-out, disabled, hint and error. All input types have the height size of 40px and they come in 5 different width sizes.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### Spacing guidelines

* Based on their width size, dropdown list menus are categorized into 5 groups: **XL**, **L**, **M**, **S** and **XS**.
* Dropdowns are mostly used in forms so the group sizes are designed to fit them perfectly.
* In forms, the total width of the dropdowns per row must be 376px, therefore use width sizes depending on how much dropdowns are needed in a single row.
* The margin between dropdowns in a single row must be 16px.

![](/assets/atoms/dropdowns-sizes.png)

```
/* Dropdown XL */
width: 376px;

/* Dropdown L */
width: 276px;

/* Dropdown M */
width: 184px;

/* Dropdown S */
width: 120px;

/* Dropdown XS */
width: 92px;
```

---

### Single-select

* Used when there are multiple choices, but only one option can be selected.
* Consider using radio buttons, as opposed to a select if there are only a couple/few options, or a simple either/or choice.
* A select also uses less space than a group of radio buttons — something to consider if your form is long, or space is limited.

##### Classic list

![](/assets/atoms/dropdowns-single-select-states.png)

```
/* Default */
background-color: $S200;
height: 40px;
padding: 0 16px;
border: 1px solid $S500;
border-radius: 3px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B100;

/* Default arrow*/
color: $B100;
margin-left: 16px;

/* On hover */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus */
border: 1px solid $G200;

/* On focus list item */
height: 48px;
padding: 0 16px 0 16px;
border-bottom: 1px solid $S500;
background: $S100;
font-family: Open Sans;
font-weight: Semibold;
color: $B200;

/* On focus list item hover */
background: $S200;

/* On focus list base */
border: 1px solid $S500;
box-shadow: 2px 2px 4px 0 #E0E0E0;
border-radius: 3px;

/* Filled out */
font-weight: Semibold;
color: $B300;

/* Disabled */
opacity: 50%;

/* Error state */
border: 1px solid $R300;

/* Error state icon */
color: $R300;

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
color: $B200;
```

---

##### Flag list

![](/assets/atoms/dropdowns-currency-states.png)

```
/* Differences compared to the Classic list */

/* On focus / flag image */
width: 24px;
height: 24px;
margin-right: 8px;

/* On focus / currency short code */
text-align: right;
float: right;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B200;

/* Filled out / flag image */
width: 24px;
height: 24px;
margin-right: 8px;

/* Filled out / currency short code */
text-align: right;
float: right;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B300;
```

---

### Multi-select

* Consider using a Dropdown Multi-select if there are several \(6+\) choices; or in cases the form is long, or space is limited.
* [Checkbox Multi-select](//atoms/checkboxes.html#multi-select) are preferable over a Dropdown Multi-select when it’s important that the user sees the options available to them, to understand and consider, versus a more passive scan of their options via a multi-select.
* Selecting an option adds a ‘tag’ for that option, which can be removed by clicking the ‘x’ icon on the tag.
* More options/tags can be added. A maximum number of options can optionally be set.

![](/assets/atoms/dropdowns-multi-select-states.png)

```
/* Differences compared to the Single-select */

/* On focus / default / checkbox base */
width: 24px;
height: 24px;
border: 1px solid $S500;
border-radius: 3px;
margin-right: 8px;

/* On focus / tags */
height: 32px;
padding: 0 32px 0 12px;
border-radius: 3px;
margin-left: 4px;
border: 1px solid $S500;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B300;

/* On focus / tags / remove icon */
color: $S500;
margin: 0 8px 0 8px;
```



