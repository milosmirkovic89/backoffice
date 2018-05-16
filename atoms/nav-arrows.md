# Nav arrows

Nav arrows are mostly used to navigate back and forth when there's no enough room for the 'Back' and 'Next' buttons, in cases such as a Calendar dialog or Tabular navigation. Nav arrows have up to 4 states, including: default, on-hover, on-focus and disabled.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines {#spacing-guidelines}

* Always use [Neutral Button](//atoms/buttons.html#neutral-buttons) type with 'Back' and 'Next' labels when there is enough room.
* Use [Arrow Icons Solid](//foundations/iconography.html#arrow-icons) with $B100 color.

#### Spacing guidelines {#spacing-guidelines}

* The width of the nav arrows is 24px.
* The height of the nav arrows is 32px.

![](/assets/atoms/nav-arrows-states.png)

```
/* Default left */
width: 24px;
height: 32px;
background-color: $S100;
border: 1px solid $S500;
border-radius: 0 3px 0 3px;
padding: 8px 4px 8px 4px;
color: $B100;

/* Default right */
width: 24px;
height: 32px;
background-color: $S100;
border: 1px solid $S500;
border-radius: 3px 0 3px 0;
padding: 8px 4px 8px 4px;
color: $B100;

/* On hover */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus */
border: 1px solid $G200;
box-shadow: 1px 1px 4px 0 $G200;

/* Disabled */
opacity: 50%;
```



