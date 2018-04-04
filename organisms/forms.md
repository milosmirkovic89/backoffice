# Forms

Besides tables, forms are mostly used organisms in the Back Office application. Due to the big number of input data per page, labels and inputs are displayed inline on desktop resolutions.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### Spacing guidelines {#spacing-guidelines}

* Form section has a padding of 32px.
* The margin between rows is 16px.
* The margin between the last input row and the action buttons is 32px. 

![](/assets/organisms/forms-spacing.png)

```
/* Form section */
padding: 32px;
```

---

##### Single-row inputs

When there is only one input per label. The height of the single-row is always 40px.

![](/assets/organisms/forms-single-input-types.png)

---

##### Multi-row inputs

When there are several inputs per label. The height of the multi-row depends on the number of inputs per label.

![](/assets/organisms/forms-multi-input-types.png)

---

##### Row hover

* Every row has a hover effect to make it easier for users to focus on an individual input or input group.
* The height of the hover background depends on the height of a row plus the additional 4px on the top and bottom.

![](/assets/organisms/forms-rows-hover.png)

```
/* Row hover */
width: 100%;
background-color: $O100;
```

---

### Labels

Labels are used inline before all text inputs, text areas, dropdowns and rest of the inputs.

#### General guidelines {#spacing-guidelines}

* For elements that are a required field, the label or legend should include an asterisk `*` after the label/legend, separated by a space \(`e.g. First name *`\)
* Only first letter of the label should be capitalized.

![](/assets/organisms/forms-labels.png)

```
/* Label base */
max-width: 376px;
height: 40px;

/* Label text */
line-height: 20px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B200;

/* Label asterisk */
color: $R300;
```

---

### Data types

Besides Input types, Dropdowns, Checkboxes and so on... Forms contain additional types of data, such as: **Texts**, [**Links**](//atoms/buttons.html#links) and **Hints**.

![](/assets/organisms/forms-data-types.png)

```
/* Data types base */
max-width: 376px;
height: 40px;

/* Texts */
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B300;

/* Links */
/* See Links section in Buttons page  */

/* Hints */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B200;
```

---

### Buttons

There are two ways to use Buttons: At the **Bottom** of the form \(applies to the entire form\) and **Inline -** next to the label or input \(applies only to the specific row where the button is\).

#### General guidelines {#spacing-guidelines}

* Always use 40px height buttons.
* Set buttons to 'Disabled' state if they have role to submit the action that is not done yet \(example: 'Save Changes' button should be displayed in 'Default' state only when some changes are made in form\).

##### Bottom

* The Primary buttons should always be displayed at the far left.
* The margin between General buttons is 16px.

![](/assets/organisms/forms-bottom-buttons.png)

---

##### Inline

* There is a margin of 8px between inputs and buttons.
* Some labels require an expanded form, in that case show an 'Edit' button just next to the label which would open a new dedicated page for the specific label \(e.g. Risk Scoring / Point Scoring\).

![](/assets/organisms/forms-inline-buttons.png)

---

### Icons

Use Icons as actions next to a data text or link.

#### Spacing guidelines {#spacing-guidelines}

* There is a margin right of 8px between text/link and icons.

![](/assets/organisms/forms-icons.png)

---

### Empty state

If there is no data to interact with show an empty state message.

![](/assets/organisms/forms-empty-state.png)

```
/* Empty state message */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B200;
```



