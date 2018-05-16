# Layout

To date, all pages in the Back Office application are using one of the three layout styles: **Layout \#1**, **Layout \#2** and **Layout \#3**.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

### Content section

* The width of the content section is set to 100%.
* Content section has `background-color: $S200`.
* Content section has a padding on all sides, top and bottom of 24px and left and right of 32px.

![](/assets/foundations/layout-content-section.png)

```
/* Content section */
width: 100%;
background-color: $S200;
padding: 24px 32px 24px 32px;
```

---

### Content wrapper

* Content wrapper has `background-color: $S100`.
* There is a solid border of 1px on all sides.
* Top left and right corners have a border radius of 3px.

![](/assets/foundations/layout-content-wrapper.png)

```
/* Content section */
background-color: $S100;
border: 1px solid $S500;
border-radius: 3px 3px 0 0;
```

---

