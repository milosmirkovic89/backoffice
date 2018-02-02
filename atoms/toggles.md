# Toggles

Toggles are a quick way to view and switch between enabled or disabled states. Toggles have up to 4 states, including default, on-hover, on-focus and disabled.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines {#general-guidelines}

* Use toggles when your intent is to turn something on or off instantly.

* Toggles should never require users to press a button to apply the settings.

* When you require users to press a submit button with a toggle, you may confuse them because it’s not the expected next step. In those cases, use [_Checkboxes_](/atoms/checkboxes.md) instead.

#### Spacing guidelines

* The width of the toggle is 48px.
* The height of the toggle is 24px.

![](/assets/atoms/toggles-states.png)

```
/* Default base */
background: $S100;
width: 48px;
height: 24px;
border: 1px solid $S400;
border-radius: 100%;

/* Default / on icons */
margin: 4px;
color: $G300;

/* Default / off icons */
margin: 4px;
color: $S500;

/* On hover base */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus base */
box-shadow: 1px 1px 4px 0 $G200;

/* Disabled */
opacity: 50%;
```



