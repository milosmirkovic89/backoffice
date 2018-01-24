# Buttons

There are 4 types of buttons: **Primary**, **Neutral**, **Positive** and **Negative**. Each button style has 5 states, including: default, on-hover, pressed, loading and disabled. All button types come in two different height sizes of 40px and 32px, except Primary button which has additional 48px height size.

**Note:** All CSS shown is for guiding purposes and it's not absolute.

### Primary buttons

Primary buttons come in 3 different height sizes: **48px**, **40px** and **32px**. Each of them has 5 states noted above.

* Action oriented button. Think: 'Done', 'Save', 'Next', 'Submit'.
* Normally\* the primary positive action in any scenario.
* Some scenarios are more suited to the **Positive** button style as the primary positive action, when the action doesn't need to be so prominent / stand-out.
* Ideally there should only be one Primary button on any screen/scenario \(the core action to proceed/progress/take action on the page\). If there isn’t any one clear primary action, then consider using one or a combination of the other button styles.

![](/assets/atoms/buttons-primary.png)

```
/* Default 32px */
background-color: $green300;
border-radius: 3px;
height: 32px;
padding: 0 12px;
transition: all 0.2s;
font-family: Montserrat;
font-size: 12px;
color: $shade100;

/* Default 40px */
background-color: $green300;
border-radius: 3px;
height: 40px;
padding: 0 16px;
transition: all 0.2s;
font-family: Montserrat;
font-size: 13px;
color: $shade100;

/* Default 48px */
background-color: $green300;
border-radius: 3px;
height: 48px;
padding: 0 24px;
transition: all 0.2s;
font-family: Montserrat;
font-size: 14px;
color: $shade100;

/* On-hover All */
background-color: $green400;

/* Pressed All */
background-color: $green500;

/* Loading icon All*/
color: $shade100;

/* Disabled All */
background-color: $green200;
```



