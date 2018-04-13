# Data tables

Data table is the most used organism in the Back Office application.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### Spacing guidelines {#general-guidelines}

* Tables use 100% width size of the content section.
* The table container has a left and right padding of 16px.

![](/assets/organisms/data-tables-spacing.png)

```
/* Table section */
width: 100%;
padding-left: 16px;
padding-right: 16px;
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

* The hight of the rows is 64px.

![](/assets/organisms/data-tables-row-spacing.png)

```
/* Rows */
height: 64px;
background-color: $S100;
border-bottom: 1px solid $S500;
```

---

### Labels

#### General guidelines

* Only the first letter of labels should be capitalized.
* There can be an icon next to the label that indicates if the data in the column can be sorted alphanumerically.Spacing guidelines.

#### Spacing guidelines

* The height of the Labels section is 40px.
* There is no margin between the label and the 'sort' icons which have have a 16x16px container.

![](/assets/organisms/data-tables-labels.png)

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

### Footer w/ pagination

Footer with a pagination contains following molecules: The dropdown option to select a number of entries per page, the '[Pagination](/molecules/pagination.md)' and the 'Go to page' option.

#### Spacing guidelines

* There is a left and right padding of 32px.
* The height of the Footer w/ pagination is 64px.

![](/assets/organisms/data-tables-footer-with-pagination-spacing.png)

```
/* Footer w/ pagination section */
width: 100%;
height: 64px;
padding-left: 32px;
padding-right: 32px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
```

---

##### Elements

* Entries per page: the margin between texts and the dropdown is 8px.
* Go to page: the margin between text and the input field is 8px.

![](/assets/organisms/data-tables-footer-with-pagination-elements.png)

```
/* Entries per page */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $B200;

/* Pagination */
See 'Pagination' in Molecules section.

/* Go to page */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $B200;
```

---

