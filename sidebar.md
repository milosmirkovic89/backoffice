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
font-family: Montserrat;
font-size: 13px;
text-transform: uppercase;

/* Primary item arrow */
width: 16px;
height: 16px;
```

---

![](/assets/organisms/sidebar-primary-item-states.png)

```
/* Default */

/* Primary item */
background-color: $B500;

/* Primary item icon */
color: $B200;

/* Primary item label */
color: $B100;
```



