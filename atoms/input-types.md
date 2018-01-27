# Input types

Below are specs for all the form input types. Each input has up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

### Sizing

Based on their width size, input types are categorized in 5 groups: **XL**, **L**, **M**, **S** and **XS**. Input types are mostly used in forms so the group sizes are designed to fit them perfectly. The total width of the input types per row must be 380px, therefore use width sizes depending on how much input fields are needed in a row.

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

Text inputs are used for simple text fields such as name, email, number or password inputs.

![](/assets/atoms/input-types-text-input-states.png)

```
/* Default */
background-color: $S100;
height: 40px;
padding: 0 16px;
border: 1px solid $S400;
border-radius: 3px;
font-family: Open Sans;
font-weight: Regular;
font-size: 13px;
color: $S500;

/* On hover */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus */
border: 1px solid $G200;
background-color: $S200;
font-weight: Semibold;
color: $B300;

/* Filled out */
font-weight: Semibold;
color: $B300;

/* Disabled */
opacity: 50%;

/* Error state */
border: 1px solid $R300;

/* Error state icon */
color: $R300;

/* Error state message */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $R300;

/* Hint message */
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $B200;
```

---

### Prefix & suffix

Useful to add extra clarity as to what is expected of a text input.

##### Prefix

![](/assets/atoms/input-types-prefix-states.png)

```
/* Prefix area */
background-color: $S200;
height: 38px;
padding: 0 16px;
border-radius: 3px 0 0 3px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B100;
```

##### Suffix

![](/assets/atoms/input-types-suffix-states.png)

```
/* Suffix area */
background-color: $S200;
height: 38px;
padding: 0 16px;
border-radius: 0 3px 3px 0;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B100;
```

---

### Value inputs

Value inputs are used for number fields only such as currency amounts. The font size is the only difference compared to text inputs.

![](/assets/atoms/input-types-value-input-states.png)

```
/* Value Input */
font-size: 15px;
```

---

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



