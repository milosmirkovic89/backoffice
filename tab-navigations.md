# Tab navigations

When there are multiple sub-pages on the screen tab navigations come into play. There are two kinds of them: **primary** and **secondary**.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

### Primary

The primary tab navigation contains the pages that are built-in the system, for example the 'Customer Information' page for a specific user \(Details, Account information, Compliance, History...\).

#### General guidelines {#spacing-guidelines}

* Only first letter of the tab label should be capitalized.
* When number of tab items exceed the width of the content wrapper use [Nav arrows](/atoms/nav-arrows.md).

#### Spacing guidelines {#spacing-guidelines}

* The height of the Primary tab navigation is 72px.
* There are paddings on the left and right of 16px.

![](/assets/organisms/tab-navigations-primary-sizing.png)

```
/* Primary */
height: 72px;
padding: 0 16px 0 16px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
```

---

##### Nav arrows

* [Nav arrows](/atoms/nav-arrows.md) should be visible only in cases when there are more items on the left or the right side, or both.
* When [Nav arrows](/atoms/nav-arrows.md) are visible there is a gradient mask of 64px in width next to them.

![](/assets/organisms/tab-navigations-primary-nav-arrows.png)

```
/* Gradient mask / left */
background-image: linear-gradient(90deg, $S100 0%, $S200 75%);

/* Gradient mask / right */
background-image: linear-gradient(-90deg, $S100 0%, $S200 75%);
```

---

Primary elements
