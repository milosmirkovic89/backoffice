# Input types

All input fields have the same height but they differ in width size which separate them in 5 group sizes: **XL**, **L**, **M**, **S** and **XS**. Input fields are mostly used in forms so the group sizes are designed to fit them perfectly. Each input has up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

### Labels

Labels are used inline before all text inputs, text areas and drop-downs. For elements that are a required field, the label or legend should include an asterisk `*` after the label/legend, separated by a space \(`e.g. First name *`\). The max width of labels is 380px.

![](/assets/atoms/intput-types-labels.png)

```
/* Label */
max-width: 380px;
height: 40px;
font-family: Open Sans;
font-weight: Regular;
line-height: 20px;
color: $B200;

/* Label Asterisk */
color: $R300;
```



