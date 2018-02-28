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

### Primary items

Primary items represent main categories of the Back Office application.

#### General guidelines {#spacing-guidelines}

* When collapsed use [Outline / down arrow icon.](//foundations/iconography.html#arrow-icons)
* When expanded use [Outline / up arrow icon.](//foundations/iconography.html#arrow-icons)

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
color: $S500;
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
color: $S500;

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

---

### Secondary items

Secondary items fall into the second level group in the navigation menu hierarchy.

#### General guidelines {#spacing-guidelines}

* When collapsed use [Outline / down arrow icon.](https://www.cymonz.design/foundations/iconography.html#arrow-icons)
* When expanded use [Outline / up arrow icon.](https://www.cymonz.design/foundations/iconography.html#arrow-icons)
* The active item has an indicator before the label; for this purpose use [Solid / right arrow icon.](//foundations/iconography.html#arrow-icons)
* There's a padding of 8px before the first and after the last secondary item.
* Secondary items should be displayed in alphabetical order.

![](/assets/organisms/sidebar-secondary-item-sizing.png)

```
/* Secondary items section */
width: 320px;
height: auto;
padding: 8px 0 8px 0;
background-color: $B400;
```

---

![](/assets/organisms/sidebar-secondary-item-sections.png)

```
/* Secondary item */
height: 40px;
padding: 0 16px 0 32px;
background-color: $B400;
```

---

![](/assets/organisms/sidebar-secondary-item-content-sizing.png)

```
/* Indicator */
width: 16px;
height: 16px;
color: $S500;
margin-right: 8px;

/* Label */
width: 216px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;

/* Arrow */
width: 16px;
height: 16px;
```

---

![](/assets/organisms/sidebar-secondary-item-states.png)

```
/* Default / tertiary item not available */

/* Indicator */
display: none;

/* Label */
color: $B100;

/* Arrow */
display: none;
```

```
/* Default / tertiary item available */

/* Indicator */
display: none;

/* Label */
color: $B100;

/* Arrow */
color: $B200;
```

```
/* On hover / tertiary item not available */

/* Indicator */
display: none;

/* Label */
color: $S500;

/* Arrow */
display: none;
```

```
/* On hover / tertiary item available */

/* Indicator */
display: none;

/* Label */
color: $S500;

/* Arrow */
color: $S500;
```

```
/* Active / tertiary item not available */

/* Indicator */
color: $S500;

/* Label */
color: $S100;

/* Arrow */
display: none;
```

```
/* Active / tertiary item available / collapsed */

/* Indicator */
color: $S500;

/* Label */
color: $S500;

/* Arrow */
color: $S500;
```

```
/* Active / tertiary item available / expanded */

/* Indicator */
color: $S500;

/* Label */
color: $S500;

/* Arrow */
color: $B200;
```

---

### Tertiary items

Tertiary items fall into the third level group in the navigation menu hierarchy.

#### General guidelines {#spacing-guidelines}

* The active item has an indicator before the label; for this purpose use [Solid / right arrow icon.](//foundations/iconography.html#arrow-icons)
* Tertiary items should be displayed in alphabetical order.

![](/assets/organisms/sidebar-tertiary-item.png)

```
/* Tertiary items section */
width: 320px;
height: auto;

/* Tertiary item */
height: 40px;
padding-left: 56px;
```

---

![](/assets/organisms/sidebar-tertiary-item-content-sizing.png)

```
/* Indicator */
width: 16px;
height: 16px;
color: $S500;
margin-right: 8px;

/* Label */
width: 216px;
font-family: Open Sans;
font-size: 13px;
```

---

![](/assets/organisms/sidebar-tertiary-item-states.png)

```
/* Default */

/* Indicator */
display: none;

/* Label */
font-weight: Regular;
color: $B100;
```

```
/* On hover */

/* Indicator */
display: none;

/* Label */
font-weight: Regular;
color: $S500;
```

```
/* Active */

/* Indicator */
display: inline;

/* Label */
font-weight: Semibold;
color: $S100;
```

---

### Minimized

The sidebar can be minimized by user or can be displayed by default on browsers with small width.

#### General guidelines {#spacing-guidelines}

* On hover, show only the Primary item label. If the mouse cursor moves away from the sidebar the dialog with Primary item label should instantly disappear.
* On press, the dialog should stay on top of everything and should disappear only if user clicks outside of it.

#### Spacing guidelines {#spacing-guidelines}

* Primary item has increased width size to 320px, because of a left padding of 56px.
* Secondary and Tertiary items keep exactly the same CSS properties.

![](/assets/organisms/sidebar-minimized-secondary-items.png)

```
/* Primary label section on Minimized Sidebar */


/* Label section */
width: 320px;
padding-right: 56px;
```

---

![](/assets/organisms/sidebar-minimized-states.png)

