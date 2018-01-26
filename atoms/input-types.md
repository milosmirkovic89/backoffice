# Input types

Below are specs for all the form input types. Each input has up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

### Sizing

All input fields have the same height but they differ in width size which separate them in 5 group sizes: **XL**, **L**, **M**, **S** and **XS**. Input fields are mostly used in forms so the group sizes are designed to fit them perfectly. The total width of the input fields must be 380px, therefore use input sizes depending on how much input fields are needed in a row.

![](/assets/atoms/input-types-input-sizes.png)

```
/* Input XL */
width: 380px;

/* Input L */
width: 281px;

/* Input M */
width: 182px;

/* Input S */
width: 116px;

/* Input XS */
width: 83px;
```

### Text inputs

Text inputs are used for simple text fields such as name, email, number or password inputs, which all use the same text input style.

![](/assets/atoms/input-types-text-input-states.png)

```
/* Text input */
background-color: $S100;
height: 40px;
padding: 0 16px;
border: 1px solid $S400;
border-radius: 3px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $B100;
```

### Labels

Labels are used inline before all text inputs, text areas and drop-downs. For elements that are a required field, the label or legend should include an asterisk `*` after the label/legend, separated by a space \(`e.g. First name *`\). The max width of labels is 380px.

![](/assets/atoms/input-types-labels.png)

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



