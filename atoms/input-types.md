# Input types

There are 5 types of input fields: **Text inputs**, **Prefix & suffix**, **Value inputs,** **Search inputs **and** Textarea**. Each of them has up to 8 states, including: default, on-hover, on-focus, filled-out, disabled, hint, error and uneditable. All input types have the height size of 40px \(except Textarea\) and they come in 5 different width sizes.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### Spacing guidelines

* Based on their width size, input types are categorized in 5 groups: **XL**, **L**, **M**, **S** and **XS**.
* Input types are mostly used in forms so the group sizes are designed to fit them perfectly.
* In forms, the total width of the input types per row must be 376px, therefore use width sizes depending on how much input fields are needed in a single row.
* The margin between input types in a single row is 16px.

![](/assets/atoms/input-types-sizes.png)

```
/* Input XL */
width: 376px;

/* Input L */
width: 276px;

/* Input M */
width: 184px;

/* Input S */
width: 120px;

/* Input XS */
width: 92px;
```

---

### Text inputs

Text inputs are used for simple text fields such as name, email address, phone number, etc.

![](/assets/atoms/input-types-text-input-states.png)

```
/* Default */
background-color: $S100;
height: 40px;
padding: 0 16px;
border: 1px solid $S500;
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

/* Error message */
margin-top: 8px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 11px;
color: $R300;

/* Hint message */
margin-top: 8px;
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

Value inputs are used for currency amount fields only. The increased font size is the only difference compared to text inputs.

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

### Auto-complete inputs

Instant search inputs are a mix of Text and Search inputs. The CSS properties are almost identical to the ones used for Text inputs just with additional Search icon on the left. Compared to the Search inputs, Instant search inputs do not have a button to submit a query. Here, the results are visible instantly in a list below as user types.

![](/assets/atoms/input-types-instant-search-states.png)

```
/* Differences compared to Text input CSS */

/* Search icon */
color: $S500;
margin-right: 8px;
```

---

### Textarea

Used when at least a sentence of text is expected or necessary to be entered.

#### General guidelines

* Consider setting a minimum 4 rows.
* The line height is set to 21px \(font size of: 13px + 8px\).
* This increases the height of the text area to 108px, making it clearer to the user that they can write more.
* When the expectation is for the user to write significantly more, consider setting the the number of rows to 10\(+\) so they know they can write more, and there’s less vertical scroll for them as they type.

![](/assets/atoms/input-types-text-area-states.png)

```
/* Differences compared to Text input CSS */

/* Default */
min-height: 108px;
line-height: 21px;
padding: 12px 16px 12px 16px;
color: $S500;

/* On focus */
color: $B200;

/* Filled out */
font-weight: Regular;
color: $B200;

/* Uneditable */
font-weight: Regular;
color: $B200;
border: none;
```



