# Data tables

Besides Forms, Data tables are the most frequently used organisms across the platform. This page contains the details about table elements, such as rows, columns, header and footer. Table data is explained in [Table cells](/molecules/table-cells.md) page.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### Spacing guidelines {#general-guidelines}

* Data tables use 100% width size of the content section.
* The table container has a left and right padding of 16px.
* The table section has a margin bottom of 32px.

![](/assets/organisms/data-tables-spacing.png)

```
/* Data table section */
width: 100%;
padding-left: 16px;
padding-right: 16px;
margin-bottom: 32px;
```

---

##### Columns {#single-row-inputs}

* The width of the columns is dynamic and it depends of the data.
* Each column has a left and right padding of 16px.

![](/assets/organisms/data-tables-column-spacing.png)

```
/* Columns */
width: auto;
padding-left: 16px;
padding-right: 16px;
```

---

##### Rows

* The height of the rows is 64px.
* There is a padding top and bottom of 12px.

![](/assets/organisms/data-tables-row-spacing.png)![](/assets/organisms/data-tables-row-padding.png)

```
/* Row */
height: 64px;
padding: 12px 0 12px 0;
background-color: $S100;
border-bottom: 1px solid $S500;
```

---

##### Row hover

* The background color of the row changes from $S100 to $O100 on hover.

![](/assets/organisms/data-tables-row-hover.png)

```
/* Row hover */
width: 100%;
background-color: $O100;
```

---

##### Row total

The background color of the Row total changes from $S100 to $G100 and it shows the total sum per column.

![](/assets/organisms/data-tables-row-total.png)

```
/* Row total */
width: 100%;
background-color: $G100;
```

---

##### Row selected

Row selection should be used whenever there are same but separate actions for each row so that user can select multiple rows  and perform a batch actions.

![](/assets/organisms/data-tables-row-selection.png)

```
/* Row selected */
width: 100%;
background-color: $G100;
```

---

##### Batch action

* The width of the batch action section is the same as the table width.
* The height of the batch action section is 64px.
* The section is positioned at the bottom of the Content wrapper on top of all other elements.
* There is a left and right padding of 32px.

![](/assets/organisms/data-tables-batch-action-section.png)

```
/* Batch action section */
width: 100%;
height: 64px;
padding: 0 32px 0 32px;
background-color: $S100;
border: 1px solid #C0C0C0;
box-shadow: 0 -4px 4px 0 $S300;
```

---

![](/assets/organisms/data-tables-batch-action-elements.png)

```
/* Left side text */
font-family: OpenSans;
font-size: 11px;
font-weight: Semibold:
color: $B200;

/* Separator */
width: 2px;
height: 16px;
background: $S400;
```

---

### Header

#### General guidelines

* Only the first letter of labels should be capitalized.
* There can be an icon next to the label that indicates if the data in the column can be sorted alphanumerically.
* Also, there are ascending and descending icons that indicate which column is currently being used for sorting.

#### Spacing guidelines

* The height of the Labels section is 40px.
* There is no margin between the label and the 'sort' icons which have have a 16x16px container.

![](/assets/organisms/data-tables-header.png)

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

##### Elements

* There is no margin between the label name and the sort icon.
* There is an 8px margin between the label name and the details icon.

![](/assets/organisms/data-tables-header-elements.png)

---

### Footer

##### With pagination

* Show pagination if there are more than 10 rows.
* There is a left and right padding of 32px.
* The height of the Footer w/ pagination is 64px.
* Limit rows per page to 500.

![](/assets/organisms/data-tables-footer-pagination.png)

```
/* Footer with pagination */
width: 100%;
height: 64px;
padding-left: 32px;
padding-right: 32px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
```

---

##### With counter

* In case there are less than 10 rows the pagination is not needed, in that case only show the row counter.
* There is a left padding of 32px.
* The height of the Footer w/ counter is 48px.

![](/assets/organisms/data-tables-footer-counter.png)

```
/* Footer with counter */
width: 100%;
height: 48px;
padding-left: 32px;
background-color: $S100;
border-top: 1px solid $S500;
```

---

##### Elements

* Entries per page: the margin between texts and the dropdown is 8px.
* Go to page: the margin between text and the input field is 8px.

![](/assets/organisms/data-tables-footer-elements.png)

```
/* Entries per page text */
font-family: OpenSans;
font-size: 11px;
font-weight: Semibold:
color: $B200;

/* Entries per page dropdown */
/* Differences compared to 'Dropdowns' in Atoms section. */
width: 72px;
height: 32px;
padding: 0 12px;

/* Pagination */
/* See 'Pagination' in Molecules section.*/

/* Go to page text */
font-family: OpenSans;
font-size: 11px;
font-weight: Semibold:
color: $B200;

/* Go to page input */
/* Differences compared to 'Input types' in Atoms section. */
width: 56px;
height: 32px;
padding: 0 12px;
```

---

### Cells

There are two different cell types that are used in tables: **Text **and **Actions.**

* Table cells are always aligned to the left.
* The height of table cells is always 40px.

![](/assets/organisms/data-tables-cell-sizing.png)

```
/* Table cells */
height: 40px;
```

---

##### Text

* The line height of the text in cells is 20px.
* If the space is limited text in cells should be displayed in two lines.

![](/assets/organisms/data-tables-cells-text.png)

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

* Use only 40px [Button](/atoms/buttons.md) size.
* Use only 'M' and 'L' size for [Dropdowns](/atoms/dropdowns.md) and [Input types](/atoms/input-types.md).
* [Toggles](/atoms/toggles.md) and [Checkboxes](/atoms/checkboxes.md) have a top and bottom margins of 8px.
* There is a margin of 8px between links and icons.

![](/assets/organisms/option-tables-cell-actions.png)

