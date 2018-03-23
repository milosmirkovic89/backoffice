# Tab navigations

When there are multiple sub-pages on the screen tab navigations come into play. There are two kinds of them: **primary** and **secondary**.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

### Primary

The primary tab navigation contains the pages that are built-in the system, for example the 'Customer Information' page for a specific user \(Details, Account information, Compliance, History...\).

#### General guidelines {#spacing-guidelines}

* Only first letter of the tab label should be capitalized.
* When number of tab items exceed the width of the content wrapper use [Nav arrows](/atoms/nav-arrows.md).
* Primary tab items should always link to the new page.

#### Spacing guidelines {#spacing-guidelines}

* The height of the Primary tab navigation is 72px.
* There are paddings on the left and right of 16px.

![](/assets/organisms/tab-navigations-primary-sizing.png)

```
/* Primary section */
height: 72px;
padding: 0 16px 0 16px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
```

---

##### Nav arrows

* [Nav arrows](/atoms/nav-arrows.md) should be visible only in cases when there are more items on the left or the right side, or both.
* When [Nav arrows](/atoms/nav-arrows.md) are visible there is a gradient mask of 32px in width next to them.

![](/assets/organisms/tab-navigations-primary-nav-arrows.png)

```
/* Nav arrow / left */
float: left;

/* Gradient mask / left */
width: 32px;
background-image: linear-gradient(90deg, $S100 0%, $S200 75%);

/* Nav arrow / left */
float: right;

/* Gradient mask / right */
width: 32px;
background-image: linear-gradient(-90deg, $S100 0%, $S200 75%);
```

---

##### Elements

![](/assets/organisms/tab-navigations-primary-items.png)

```
/* Primary item / base */
height: 48px;
padding: 16px;


/* Primary item / default */
height: 16px;
padding: 0 16px 0 16px;
border-right: 2px solid $S400;
font-family: OpenSans;
font-size: 13px;
font-weight: Semibold:
text-align: center;
color: $B200;

/* Primary item / on-hover */
color: $S500;

/* Primary item / on-hover */
color: $B100;

/* Primary item / on-hover */
color: $G300;
```

---

### Secondary

The secondary tab navigation is data-driven, therefore the admin or users need to make an action that will create the tab items \(example: currency list in 'Trading Time'\).

#### General guidelines {#spacing-guidelines}

* Only first letter of the tab label should be capitalized.
* When number of tab items exceed the width of the content wrapper use [Nav arrows](/atoms/nav-arrows.md).
* When switching between secondary tab items only the data below should be changed, no new page should be opened.

#### Spacing guidelines {#spacing-guidelines}

* The height of the Secondary tab navigation is 56px.
* There are paddings on the left and right of 16px.

![](/assets/organisms/tab-navigations-secondary-sizing.png)

```
/* Secondary base */
height: 56px;
padding: 0 32px 0 32px;
background-color: $S200;
border-top: 1px solid $S500;
border-bottom: 1px solid $S500;
```

---

##### Nav arrows

* [Nav arrows](/atoms/nav-arrows.md) should be visible only in cases when there are more items on the left or the right side, or both.
* When [Nav arrows](/atoms/nav-arrows.md) are visible there is a gradient mask of 32px in width next to them.

![](/assets/organisms/tab-navigations-secondary-nav-arrows.png)

```
/* Nav arrow / left */
float: left;

/* Gradient mask / left */
width: 32px;
background-image: linear-gradient(90deg, $S100 0%, $S200 75%);

/* Nav arrow / left */
float: right;

/* Gradient mask / right */
width: 32px;
background-image: linear-gradient(-90deg, $S100 0%, $S200 75%);
```

---

##### Elements

![](/assets/organisms/tab-navigations-secondary-items.png)

```
/* Secondary item / default */
height: 16px;
padding: 0 16px 0 16px;
border-right: 2px solid $S400;
font-family: OpenSans;
font-size: 13px;
font-weight: Semibold:
text-align: center;
color: $B200;

/* Primary item / on-hover */
color: $S500;

/* Primary item / on-hover */
color: $B100;

/* Primary item / on-hover */
color: $G300;
```



