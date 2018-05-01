# Table cells

There are two different cell types that are used in tables: **Data text** and **Actions**.

#### General guidelines {#general-guidelines}

* Table cells are always aligned to the left.

#### Spacing guidelines {#general-guidelines}

* The height of table cells is always 40px.

![](/assets/molecules/table-cells-sizing.png)

```
/* Table cells */
height: 40px;
```

---

### Data text

* The line height of the data text is 20px.
* If the space is limited data text should be displayed in two lines.

![](/assets/molecules/table-cells-data-text.png)

```
/* Data text */
line-height: 20px;

/* Default */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $B200;

/* Green */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $G300;

/* Orange */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $O300;

/* Red */
font-family: OpenSans;
font-size: 13px;
font-weight: Regular:
color: $R300;

/* Hint */
font-family: OpenSans;
font-size: 11px;
font-weight: Semibold:
color: $B200;

/* Large */
font-family: OpenSans;
font-size: 15px;
font-weight: Semibold:
color: $B300;
```

---

### Actions

* Use only 40px [Button](/atoms/buttons.md) size.
* Use only 'M' and 'L' size for [Dropdowns](/atoms/dropdowns.md) and [Input types](/atoms/input-types.md).

![](/assets/molecules/table-cells-actions.png)

