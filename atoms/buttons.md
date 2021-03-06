# Buttons

There are 5 types of buttons: **Primary**, **Positive, Negative,** **Neutral **and** Links**. Each button style has up to 5 states, including default, on-hover, pressed, loading and disabled. Button types come in three different height size of 48px, 40px and 32px, except Links which do not have a base.

**Note:** All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines

* Montserrat typeface should be always used for the text on buttons \(except Links\).
* There should be no icons on any type of buttons.
* There is a subtle fade transition from normal to hover state on buttons \(_transition: all 0.2s;_\).
* Loading animation on buttons can be found [here](https://projects.lukehaas.me/css-loaders/).

#### Spacing guidelines

* Depending on the height size, buttons have left and right padding of 12px, 16px, or 24px \(except Links\).
* Buttons contained in narrow spaces \(e.g. quote screen\) should fill 100% of the width available to them.
* If multiple buttons are horizontally aligned, there should be a 16px margin separating them.
* If the button is linked to the input field \(e.g. search input\) then the margin between should be 8px. 

##### Padding

![](/assets/atoms/buttons-padding.png)

##### Margin

![](/assets/atoms/buttons-margin.png)

### Primary buttons

Primary buttons come in 3 different height sizes: **48px**, **40px** and **32px**. Each of them has 5 states noted above.

* Action oriented button. Think: 'Save', 'Next', 'Submit'.
* Normally the primary positive action in any scenario.
* Some scenarios are more suited to the **Positive** button style as the primary positive action, when the action doesn't need to be so prominent / stand-out.
* Ideally there should only be one Primary button on any screen/scenario \(the core action to proceed/progress/take action on the page\).

![](/assets/atoms/buttons-primary.png)

```
/* Default All */
background-color: $green300;
border-radius: 3px;
transition: all 0.2s;
font-family: Montserrat;
font-weight: Semibold;
color: $S100;

/* Default 32px */
height: 32px;
padding: 0 12px;
font-size: 12px;

/* Default 40px */
height: 40px;
padding: 0 16px;
font-size: 13px;

/* Default 48px */
height: 48px;
padding: 0 24px;
font-size: 14px;

/* On-hover All */
background-color: $G400;

/* On-focus All */
background-color: $G500;

/* Loading Icon All*/
color: $shade100;

/* Disabled All */
opacity: 33%;
```

---

### Positive buttons

Positive buttons come in 2 different height sizes: **40px** and **32px**. Each of them has 5 states noted above.

* Action oriented button. Think: 'Update', 'Approve, 'Add'.
* Normally the secondary positive action in any scenario.
* Similar to the Primary button, but intended to play a more supportive or less important action button role.

![](/assets/atoms/buttons-positive.png)

```
/* Default All */
background-color: $S200;
border-radius: 3px;
border: 1px solid $S500;
transition: all 0.2s;
font-family: Montserrat;
font-weight: Semibold;
color: $G300;

/* Default 32px */
height: 32px;
padding: 0 12px;
font-size: 12px;

/* Default 40px */
height: 40px;
padding: 0 16px;
font-size: 13px;

/* On-hover All */
background-color: $S300;

/* On-focus All */
background-color: $S400;

/* Loading Icon All*/
color: $G300;

/* Disabled All */
opacity: 33%;
```

---

### Negative buttons

Negataive buttons come in 2 different height sizes: **40px** and **32px**. Each of them has 5 states noted above.

* Action oriented button. Think: 'Close', 'Delete', 'Suspend'.
* Any negative action in any scenario.

![](/assets/atoms/buttons-negative.png)

```
/* Default All */
background-color: $S200;
border-radius: 3px;
border: 1px solid $S500;
transition: all 0.2s;
font-family: Montserrat;
font-weight: Semibold;
color: $R300;

/* Default 32px */
height: 32px;
padding: 0 12px;
font-size: 12px;

/* Default 40px */
height: 40px;
padding: 0 16px;
font-size: 13px;

/* On-hover All */
background-color: $S300;

/* On-focus All */
background-color: $S400;

/* Loading Icon All*/
color: $red300;

/* Disabled All */
opacity: 33%;
```

---

### Neutral buttons

Neutral buttons come in 2 different height sizes: **40px** and **32px**. Each of them has 5 states noted above.

* Ideal for tertiary actions such as: 'Browse', 'Details, 'Edit'.
* Similar to the Positive button, but intended to play a more supportive or less important action button role.

![](/assets/atoms/buttons-neutral.png)

```
/* Default All */
background-color: $S200;
border-radius: 3px;
border: 1px solid $S500;
transition: all 0.2s;
font-family: Montserrat;
font-weight: Semibold;
color: $B200;

/* Default 32px */
height: 32px;
padding: 0 12px;
font-size: 12px;

/* Default 40px */
height: 40px;
padding: 0 16px;
font-size: 13px;

/* On-hover All */
background-color: $S300;

/* On-focus All */
background-color: $S400;

/* Loading Icon All*/
color: $black300;

/* Disabled All */
opacity: 33%;
```

---

### Links

In other words, Links are text-only buttons with underline text decoration and they are mostly used in Forms and Tables.

* Ideal for actions such as: 'View', '\(name of the page/document\).
* Links have only four states: Default, On-hover, On-focus and Disabled.

![](/assets/atoms/buttons-links.png)

```
/* Default */
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
text-decoration: underline;
color: $G300;

/* On-hover */
opacity: 80%;

/* On-focus */
opacity: 60%;

/* Disabled */
opacity: 33%;
```



