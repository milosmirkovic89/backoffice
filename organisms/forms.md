# Forms

Besides tables, forms are mostly used organisms in the Back Office application. Due to the big number of input data per page, labels and inputs are displayed inline on desktop resolutions.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines {#spacing-guidelines}

* On desktop resolutions, labels and inputs are displayed inline.

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

### Labels

Labels are used inline before all text inputs, text areas, dropdowns and rest of the inputs.

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

### Inputs

Inputs can be displayed in a **Single-row **\(when there is only one input per label\)** **or **Multi-rows **\(where there are several inputs per label\).

##### Single-row

* The height of the single-row input is always 40px.
* If an input is smaller than 40px there should be a top and bottom padding \(example: when using checkmarks there is an 8px padding\). 

![](/assets/organisms/forms-single-input-types.png)

##### Multi-rows

* Grouped inputs should always be displayed under each other.
* The padding between grouped inputs is always 8px.
* The first checkmark in a group \(24px\) has a padding top of 8px.
* The last checkmark in a group \(24px\) has a padding top of 8px.
* The first radio button in a group \(20px\) has a padding top of 10px.
* The last checkmark in a group \(20px\) has a padding top of 10px.

![](/assets/organisms/forms-multi-input-types.png)

##### Row hover

* Every row has a hover effect to make it easier for users to focus on an individual input.
* The height of the hover background depends on the height of a row plus the additional 4px on the top and bottom.

![](/assets/organisms/forms-rows-hover.png)

```
/* Row hover */
width: 100%;
background-color: $O100;
```

---



