# Option tables

Option tables are a mix of the [Data tables](/organisms/data-tables.md) and [Forms](/organisms/forms.md). They are displayed in columns and rows, as Data tables, but they do not show data, they show options similar to those we have in Forms. The number of rows is limited and small so the footer with pagination or counter is not required.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### Spacing guidelines {#general-guidelines}

* Option tables use 100% width size of the content section.
* The table container has a left and right padding of 16px.

![](/assets/organisms/option-tables-spacing.png)

```
/* Option table section */
width: 100%;
padding-left: 16px;
padding-right: 16px;
```

---

##### Columns {#single-row-inputs}

* The width of the columns is dynamic and it depends of the content.
* Each column has a left and right padding of 16px.

![](/assets/organisms/option-tables-column-spacing.png)

```
/* Columns */
width: auto;
padding-left: 16px;
padding-right: 16px;
```

---

##### Rows {#rows}

* The height of rows is 40px.
* There is a margin between each row of 16px.
* The first row has a margin top of 32px.
* The last row has a margin bottom of 32px.

![](/assets/organisms/option-tables-row-sizing.png)![](/assets/organisms/option-tables-row-spacing.png)

```
/* Row */
height: 40px;
```

---

##### Row hover {#row-hover}

* Every row has a hover effect to make it easier for users to focus on an individual input or input group.
* The height of the hover is 48px.

![](/assets/organisms/option-tables-row-hover.png)

```
/* Row hover */
width: 100%;
background-color: $O100;
```

---

### Header {#header}

#### General guidelines {#general-guidelines}

* Only the first letter of labels should be capitalized.

#### Spacing guidelines {#spacing-guidelines}

* The height of the Labels section is 40px.

![](/assets/organisms/option-tables-header.png)

```
/* Label section */
height: 40px;
background-color: $S200;
border-bottom: 1px solid $S500;

/* Label */
font-family: OpenSans;
font-size: 12px;
font-weight: Semibold:
color: $B200;
```

---

### Cells

There are two different cell types that are used in tables: **Text **and **Actions.**

* Cells are always aligned to the left.
* The height of cells is always 40px.

![](/assets/organisms/option-tables-cell-sizing.png)

```
/* Cells */
height: 40px;
```

---

##### Text

* The line height of the text in cells is 20px.
* If the space is limited text in cells should be displayed in two lines.

![](/assets/organisms/option-tables-cells-text.png)

```
/* Default */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $B200;
line-height: 20px;

/* Green */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $G300;
line-height: 20px;

/* Orange */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $O300;
line-height: 20px;

/* Red */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $R300;
line-height: 20px;

/* Hint */
font-family: OpenSans;
font-size: 11px;
font-weight: Semibold:
color: $B200;
line-height: 20px;

/* Large */
font-family: OpenSans;
font-size: 15px;
font-weight: Semibold:
color: $B300;
line-height: 20px;
```

---

##### Actions

* Use only 40px [Button](https://www.cymonz.design/atoms/buttons.html) size.
* [Toggles](https://www.cymonz.design/atoms/toggles.html) and [Checkboxes](https://www.cymonz.design/atoms/checkboxes.html) have a top and bottom margins of 8px.
* There is a margin of 8px between links and icons.

![](/assets/organisms/option-tables-cell-actions.png)

