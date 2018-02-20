# Date picker

Date pickers are mostly used in forms as data inputs or in header sections as data result filters. The data picker has two elements: **input base** and **calendar dialog**. The input base has up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

### Input base

#### General guidelines {#spacing-guidelines}

* The CSS of [Dropdowns](//atoms/dropdowns.html) is applied to the input base with one difference, the calendar icon is used instead of a caret arrow.

#### Spacing guidelines {#spacing-guidelines}

* In forms, the input base is displayed in full width size of 380px \(XL\).
* In header sections, the width of the input base is 182px \(M\).

![](/assets/molecules/data-picker-input-base-sizing.png)

```
/* Form input */
width: 380px;

/* Filter input */
width: 182px;
```

---

![](/assets/molecules/data-picker-input-base-states.png)

```
/* Default */
background-color: $S200;
height: 40px;
padding: 0 16px;
border: 1px solid $S400;
border-radius: 3px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B100;

/* Default icon*/
color: $S500;
margin-left: 16px;

/* On hover */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus */
border: 1px solid $G200;

/* On focus icon */
color: $G300;

/* Filled out */
font-weight: Semibold;
color: $B300;

/* Filled out icon */
color: $G300;

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

### Calendar dialog

#### General guidelines {#spacing-guidelines}

* The calendar dialog is displayed on top of everything when the input base is clicked.
* [Nav arrows](#) are used to navigate through the calendar.

#### Spacing guidelines {#spacing-guidelines}

* The calendar dialog has always a fixed width size of 320px.
* The base has a padding of 8px and a top margin of 8px.

##### Calendar base

![](/assets/molecules/data-picker-calendar-base.png)

```
/* Calendar dialog base */
width: 320px;
height: auto;
padding: 8px;
border: 1px solid $S500;
border-radius: 3px;
background-color: $S100;
```

---

##### Months and years

![](/assets/molecules/data-picker-calendar-months-and-years.png)

```
/* Months and years */
width: 148x;
height: 56px;
border: 1px solid $S500;
border-radius: 3px 0 0 0;
background-color: $S200;
font-family: Open Sans;
font-weight: Semibold;
font-size: 15px;
text-align: center;
color: $B300;
```

---

##### Week

![](/assets/molecules/data-picker-calendar-week.png)

```
/* Week */
width: 40px;
height: 24px;
background-color: $S100;
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
text-align: center;
color: $B200;
```

---

##### Days

![](/assets/molecules/data-picker-calendar-days.png)

```
/* Days */
width: 40px;
height: 40px;
background-color: $S200;
border: 1px solid $S500;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
text-align: center;
color: $B300;
```



