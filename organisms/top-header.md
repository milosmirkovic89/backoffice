# Top header

In other words, the main header on all pages across the back office application. It contains breadcrumbs, language, support and account options.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines {#general-guidelines}

* The breadcrumb section uses `float: left;`
* The language, support and account options use `float: right;`
* The top header should always be visible, the content below should scroll under it.

#### Spacing guidelines {#spacing-guidelines}

* The height of the top header should always be 72px.
* The width of the top header depends on browser width.

![](/assets/organisms/top-header-sizing.png)![](/assets/organisms/top-header-spacing.png)

```
/* Top header */
width: 100px;
height:72px;
padding: 0 32px 0 32px;
background-color: $S100;
border-bottom: 1px solid $S400;
```

---

### Breadcrumbs

The main purpose of breadcrumbs is to enhance the way users find their way around.

#### General guidelines {#general-guidelines}

* The current version of the application does not need more then four-level breadcrumbs, but if needed the same pattern can be used to increase the number of levels.
* The last link in the breadcrumbs section shows the current location and it's not clickable.
* Always use ALL CAPS for breadcrumb links.
* Use [Arrow Icons Outline](//foundations/iconography.html#arrow-icons) with $S500 color between links. 

#### Spacing guidelines {#spacing-guidelines}

* Arrow icons have the left and right margin of 8px.

![](/assets/organisms/top-header-breadcrumbs.png)

```
/* Link default */
font-family: Montserrat;
font-size: 13px;
text-transform: uppercase;
color: $B200;

/* Link on hover */
color: $G300;

/* Link current */
color: $S500;

/* Arrow */
color: $S500;
```

---

### Languages

A simple dropdown list to change the language of the application.

#### General guidelines {#general-guidelines}

* Always use short language codes.
* Always use ALL CAPS for language codes.
* Always list languages alphabetically.
* Use 'S' size [Flag Dropdown](//atoms/dropdowns.html#flag-list) list.

#### Spacing guidelines {#spacing-guidelines}

* The languages section has a right margin of 32px.

![](/assets/organisms/top-header-languages.png)

```
/* Languages section */
margin-right: 32px;

/* Languages section flag */
width: 24px;
height: 24px;
margin-right: 8px;

/* Languages section text */
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
text-transform: uppercase;
color: $B200;
margin-right: 4px;

/* Languages section arrow */
color: $S500;

/* Use Dropdown Flag list style for dropdown option */
```

---

### Links

Currently, there's only one link for the support in the top header section, but if needed use the same style for any other.

![](/assets/organisms/top-header-links.png)

```
/* Default */
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B200;
margin-right: 32px;

/* On hover */
color: $G300;
```

---

### User

A simple dropdown list of the logged-in user options.

#### General guidelines {#general-guidelines}

* User section should always be at the far right of the top header.
* Dropdown list items are aligned to the right.
* Use 'M' size [Single-select Dropdown](//atoms/dropdowns.html#single-select) list.

![](/assets/organisms/top-header-user.png)

```
/* User section text */
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
text-align: right;
color: $B200;
margin-right: 4px;

/* User section arrow */
color: $S500;
```



