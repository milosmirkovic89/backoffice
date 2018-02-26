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

/* Sidebar minimized */
width: 56px;
```

---

### Header

The header contains only the logo and the minimize/maximize icon.

![](/assets/organisms/sidebar-header-spacing.png)

```
/* Header */
padding: 0 12px 0 16px;
background-color: $B400;
height: 72px;

/* Header minimized */
padding: 0 12px 0 12px;
```

---

![](/assets/organisms/sidebar-header-sizing.png)

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

![](/assets/organisms/sidebar-header-hover.png)

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



