# Sidebar

The sidebar is the main navigation menu that contains the links to all pages in the Back Office application. The sidebar is fixed to the left side of the browser and can be minimized to save some space on smaller screens.

#### General guidelines {#spacing-guidelines}

* The sidebar has a separate vertical scroll.
* It contains a header, primary, secondary and tertiary links.

#### Spacing guidelines {#spacing-guidelines}

* The sidebar has a fixed width of 320px.
* The minimized version has a fixed width of 56px.

![](/assets/organisms/sidebar-sizing.png)

```
/* Sidebar */
width: 320px;
height: 72px;

/* Sidebar minimized */
width: 56px;
```

---

### Header

The header contains only the logo and the icon to minimize/maximize the sidebar.

##### Spacing

![](/assets/organisms/sidebar-header-spacing.png)

```
/* Header */
padding: 0 12px 0 16px;

/* Header minimized */
padding: 0 12px 0 12px;
```

---

##### Sizing

![](/assets/organisms/sidebar-header-sizing.png)

```
/* Logo */
max-height: 40px;

/* Minimize/Maximize icon base */
width: 32px;
height: 32px;
padding: 8px;
```



