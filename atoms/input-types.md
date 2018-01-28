# Input types

There are 5 types of input fields: **Text inputs**, **Prefix & suffix**, **Value inputs,** **Search inputs **and** Textarea**. Each of them has up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error. All input types have the height size of 40px \(except textarea\) and they come in 5 different width sizes.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### Spacing guidelines

* Based on their width size, input types are categorized in 5 groups: **XL**, **L**, **M**, **S** and **XS**.
* Input types are mostly used in forms so the group sizes are designed to fit them perfectly.
* The total width of the input types per row must be 380px, therefore use width sizes depending on how much input fields are needed in a single row.
* The margin between input types in a single row must be 16px.

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

Text inputs are used for simple text fields such as name, email address, phone number, etc.

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
/* Differences compared to Text input CSS */

/* Prefix */
background-color: $S200;
height: 38px;
padding: 0 16px;
border-radius: 3px 0 0 3px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B100;
```

---

##### Suffix

![](/assets/atoms/input-types-suffix-states.png)

```
/* Differences compared to Text input CSS */

/* Suffix */
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

Value inputs are used for currency amount fields only. The increased font size of 2px is the only difference compared to text inputs.

![](/assets/atoms/input-types-value-input-states.png)

```
/* Differences compared to Text input CSS */

/* Value input */
font-size: 15px;
```

---

### Search inputs

Search inputs use the same style as text inputs with additional search button on the right side.

![](/assets/atoms/input-types-search-states.png)

```
/* Differences compared to Text input CSS */

/* Search input */
background-color: $S200;
height: 40px;
width: 48px;
border-radius: 0 3px 3px 0;

/* Search icon */
color: $S500;

/* Search input on focus */
background-color: $G300;

/* Search icon on focus */
color: $G200;
```

---

### Textarea

Used when at least a sentence of text is expected or necessary to be entered. Consider setting a minimum 4 rows. This increases the height of the text area to 106px, making it clearer to the user that they can write more. When the expectation is for the user to write significantly more, consider setting the the number of rows to 10\(+\) so they know they can write more, and there’s less vertical scroll for them as they type.

![](/assets/atoms/input-types-text-area-states.png)

```
/* Differences compared to Text input CSS */

/* Default */
min-height: 106px;
line-height: 21px;
color: $S500;

/* On focus */
font-weight: Regular;
color: $B200;

/* Filled out */
font-weight: Regular;
color: $B200;
```



