# Headers

Because of complexity of the app there is a need for different types of content headers: **Header \#1**, **Header \#2**, **Header \#3 **and **Header \#4.**

**Note: **All CSS shown is for guiding purposes and it's not absolute.

### Header \#1

Header \#1 is the main content header of the Back Office application and it indicates the page that user selected from the Sidebar.

#### General guidelines {#general-guidelines}

* There can be only one Header \#1 per page.

#### Spacing guidelines {#general-guidelines}

* Header \#1 use 100% width size of the content section.
* Header \#1 has a hight size of 88px.

![](/assets/organisms/headers-header-1-sizing.png)

```
/* Header #1 */
height: 88px;
padding: 0 32px 0 32px;
background-color: $S100;
border-radius: 3px 3px 0 0;
border-bottom: 1px solid $S500;
border-left: 8px solid $G200;
```

---

##### Left side

* Besides the name of the page, the left side of the Header \#1 is reserved to show additional dropdown options or additional information such as the status of customers \(active, disabled...\).
* The first letter of every word should be capitalized, \(except for "and", "of", "in"...\).
* The margin between elements is always 16px.
* The margin between elements in a group is always 8px.
* Group elements are always divided by the separator.
* Use 'M' size for [Dropdowns.](/atoms/dropdowns.md)

![](/assets/organisms/headers-header-1-spacing-left.png)

##### Elements

![](/assets/organisms/headers-header-1-atoms-left.png)

```
/* Headline #1 */
font-family: OpenSans;
font-size: 19px;
font-weight: Regular:
color: $B300;

/* Status tag / active */
background: $G200;
border-radius: 3px;
padding: 0 8px 0 8px;
font-family: OpenSans;
font-weight: Semibold:
font-size: 11px;
color: $G300;

/* Status tag / disabled */
background: $R200;
border-radius: 3px;
padding: 0 8px 0 8px;
font-family: OpenSans;
font-weight: Semibold:
font-size: 11px;
color: $R300;

/* Separator */
width: 2px;
height: 16px;
background: $S400;

/* Dropdown label */
font-family: OpenSans;
font-weight: Regular;
font-size: 13px;
color: $B200;

/* Dropdown */
/* Use Dropdown Single-select at size M */

/* Security question icon */
/* Use Help icon from UI Icons */
```

---

##### Right side

* In cases where there is an additional level of hierarchy, such as 'Client Information' for specific user, there is an 'X' \(close\) button on the far right.
* The right side of the Header \#1 is reserved for various action buttons as well as the search function and the date range filters.
* The margin between elements is always 16px.
* The margin between elements in a group is always 8px.
* Group elements are always divided by the separator.
* Use 'M' size for [Dropdowns.](/atoms/dropdowns.md)
* Use 'M' size for [Input types](/atoms/input-types.md).
* Use 40px hight size [Buttons](/atoms/buttons.md).

![](/assets/organisms/headers-header-1-spacing-right.png)

##### Elements

![](/assets/organisms/headers-header-1-atoms-right.png)

```
/* Close button / default */
width: 40px;
height: 40px;
background: $S100;
border: 1px solid $S500;
border-radius: 3px;
color: $S500;

/* Close button / on hover */
background: $S200;

/* Close button / on focus */
background: $S300;

/* Button / primary */
/* Use 40 height size  */

/* Button / positive */
/* Use 40 height size  */

/* Button / negative */
/* Use 40 height size  */

/* Button / neutral */
/* Use 40 height size  */

/* Dropdown */
/* Use Dropdown Single-select at size M */

/* Search input */
/* Use size M */

/* Date picker */
/* Use size M */

/* Separator */
width: 2px;
height: 16px;
background: $S400;
```

---

### Header \#2

Header \#2 is the secondary header of the application with very small differences compared to the Header \#1. The details below contain only those differences.

#### General guidelines {#general-guidelines}

* There can be multiple Header \#2 per page.

![](/assets/organisms/headers-header-2-sizing.png)

```
/* Differences compared to the Header #1 */

/* Header #2 */
height: 88px;
padding: 0 32px 0 32px;
background-color: $S100;
border-radius: 0;
border-bottom: 1px solid $S500;
border-left: 0;
```

---

##### Left side

* Only the first letter of the headline should be capitalized.

![](/assets/organisms/headers-header-2-spacing-left.png)

##### Elements

![](/assets/organisms/headers-header-2-atoms-left.png)

```
/* Differences compared to the Header #1 */

/* Headline #2 */
font-family: OpenSans;
font-size: 15px;
font-weight: Regular:
color: $B300;
```

---

##### Right side

* There is no 'X' \(close\) button in Header \#2.

```
/* The right side of the Header #2 use the same CSS properties as Header #1 */
```

---

### Header \#3

When there are multiple sections that fall into the same category we should use Header \#3 to group the elements in it \(example: 'Buy time' and 'Sell time' on the 'Trading time' page\). Header \#3 can be used in **full width** size or as a **column** header on pages such as 'CP Statements'. Also, there's an additional Header \#3 that contains **toggle** switch actions.

##### Full width

This is the most common use of Header \#3 with a full width related to the main content wrapper.

![](/assets/organisms/headers-header-3-full.png)

```
/* Header #3 / full width */
height: 48px;
padding-left: 32px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
border-left: 8px solid $O200;
```

---

##### Column

Sometimes there is a need to have separated two-column layout within the main content wrapper. In this cases Header \#3 is used as a Column header.

![](/assets/organisms/headers-header-3-column.png)

```
/* Header #3 / column */
/* Use exactly the same CSS properties as Header #3 / full width */
```

---

##### Toggle

Use [toggles](/atoms/toggles.md) when an option to activate or disable the form below the Header \#3 is needed \(example: 'Transaction Monitoring Settings / Transactions'\).

* There is an 8px margin between toggles and headlines.
* Use 'M' size for [Dropdowns.](/atoms/dropdowns.md)

![](/assets/organisms/headers-header-3-toggle.png)

```
/* Header #3 / toggle */
/* Use exactly the same CSS properties as Header #3 / full width */
```

---

##### Elements

![](/assets/organisms/headers-header-3-atoms.png)

```
/* Headline #3 */
font-family: OpenSans;
font-size: 13px;
font-weight: Semibold:
color: $B200;

/* Toggle / off */
/* See Toggles in Atoms category   */

/* Toggle / on */
/* See Toggles in Atoms category   */

/* Dropdown */
/* Use size M */
```

---

### Header \#4

Header \#4 is mostly used in pages that use the grid layout such as 'Quote Screen' or 'CP Statements'. The style of the Header \#4 is very similar to label row in tables.

![](/assets/organisms/headers-header-4-sizing.png)

```
/* Header #3 */
height: 40px;
padding-left: 32px;
background-color: $S200;
```

---

##### Elements

![](/assets/organisms/headers-header-4-atoms.png)

```
/* Headline #4 */
font-family: OpenSans;
font-size: 12px;
font-weight: Semibold:
color: $B200;
```



