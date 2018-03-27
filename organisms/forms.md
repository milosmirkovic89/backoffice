# Forms

Besides tables, forms are mostly used organisms in the Back Office application. Due to the big number of input data per page, labels and input types are displayed inline on desktop resolutions.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines {#spacing-guidelines}

* On desktop resolutions labels and inputs are displayed inline.

#### Spacing guidelines {#spacing-guidelines}

* Form section has a padding of 32px.
* The height of rows is 40px.
* The padding between rows is 16px.
* The padding between the last data row and action buttons at the bottom is 32px. 

![](/assets/organisms/forms-spacing.png)

```
/* Form section */
padding: 32px;
```

---

![](/assets/organisms/forms-sizing.png)

```
/* Row */
hight: 40px;
```

---

### Labels

Labels are used inline before all text inputs, text areas, dropdowns and rest of the input fields.

#### General guidelines {#spacing-guidelines}

* For elements that are a required field, the label or legend should include an asterisk `*` after the label/legend, separated by a space \(`e.g. First name *`\)

* Only first letter of the label should be capitalized.

![](/assets/organisms/forms-labels-sizing.png)

```
/* Label section */
width: 380px;
height: 40px;

/* Label / default */
line-height: 20px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B200;

/* Label / important / asterisk */
color: $R300;

/* Label / two rows */
/* Same as Label / default */

/* Label / message */
font-weight: Semibold;
font-size: 11px;
color: $B200;
```

---



