# Sidebar

The sidebar is the main navigation menu that contains the links to all pages in the Back Office application. The sidebar is fixed to the left side of the browser and can be minimized to save some space on smaller screens.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines {#spacing-guidelines}

* The sidebar has a separate vertical scroll.
* It contains a header, primary, secondary and tertiary links.

#### Spacing guidelines {#spacing-guidelines}

* The sidebar has a fixed width of 320px.
* The minimized version has a fixed width of 56px.
* The height of the header is 72px.

![](/assets/organisms/sidebar-sizing.png)

```
/* Sidebar */
width: 320px;
background-color: $B500;

/* Sidebar minimized */
width: 56px;
```

---

### Header

The header contains only the logo and the minimize/maximize icon.

![](/assets/organisms/sidebar-header-sizing.png)![](/assets/organisms/sidebar-header-spacing.png)

```
/* Header */
width: 320px;
height: 72px;
padding: 0 12px 0 16px;
background-color: $B400;

/* Header minimized */
width: 56px;
padding: 0 12px 0 12px;
```

---

![](/assets/organisms/sidebar-header-content.png)

```
/* Logo section */
max-height: 40px;

/* Minimize/Maximize icon section */
width: 32px;
height: 32px;
padding: 8px;
background-color: $B500;
border-radius: 3px;
```

---

![](/assets/organisms/sidebar-header-content-hover.png)

```
/* Logo default */
opacity: 75%;

/* Logo on hover */
opacity: 100%;

/* Minimize/Maximize icon default */
color: $B200;

/* Minimize/Maximize icon on hover */
color: $S500;
```

---

### Primary item

Primary items represent main categories of the Back Office application.

#### General guidelines {#spacing-guidelines}

* When collapsed use Outline / down arrow icon.
* When expanded use Outline / up arrow icon.

![](/assets/organisms/sidebar-primary-item-sizing.png)

```
/* Primary item */
width: 320px;
height: 72px;

/* Primary item minimized */
width: 56px;
```

---

![](/assets/organisms/sidebar-primary-item-sections.png)

```
/* Icon section */
width: 56px;
padding: 0 16px 0 16px;

/* Label section */
width: 264px;
padding-right: 16px;
```

---

![](/assets/organisms/sidebar-primary-item-content-sizing.png)

```
/* Icon */
width: 24px;
height: 24px;

/* Label */
width: 216px;
font-family: Montserrat;
font-size: 13px;
text-transform: uppercase;

/* Arrow */
width: 16px;
height: 16px;
```

---

![](/assets/organisms/sidebar-primary-item-states.png)

```
/* Default */

/* Icon section */
background-color: $B500;

/* Label section */
background-color: $B500;
border-bottom: 1px solid $B400;

/* Icon */
color: $B200;

/* Label */
color: $B100;

/* Arrow */
display: none;
```

```
/* On hover / secondary items not available */

/* Icon section */
background-color: $B400;

/* Label section */
background-color: $B400;
border-bottom: none;

/* Icon */
color: $S500;

/* Label */
color: $S300;
```

```
/* On hover / secondary items available */

/* Icon section */
background-color: $B400;

/* Label section */
background-color: $B400;
border-bottom: none;

/* Icon */
color: $S500;

/* Label */
color: $S300;

/* Arrow */
display: inline;
color: $S500;
```

```
/* Active / secondary items not available */

/* Icon section */
background-color: $B400;

/* Label section */
background-color: $B400;
border-bottom: none;

/* Icon */
color: $G300;

/* Label */
color: $S300;
```

```
/* Active / secondary items available / collapsed */

/* Icon section */
background-color: $B400;

/* Label section */
background-color: $B400;
border-bottom: none;

/* Icon */
color: $G300;

/* Label */
color: $S300;

/* Arrow */
display: inline;
color: $S500;
```

```
/* Active / secondary items available / expanded */

/* Icon section */
background-color: $B400;

/* Label section */
background-color: $B400;
border-bottom: 1px solid $B500;

/* Icon */
color: $G300;

/* Label */
color: $S300;

/* Arrow */
display: inline;
color: $B200;
```



