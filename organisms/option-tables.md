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
* There is a padding top and bottom of 12px.

![](/assets/organisms/option-tables-row-sizing.png)![](/assets/organisms/option-tables-row-spacing.png)

