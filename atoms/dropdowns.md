# Dropdowns

Dropdown list menus can be categorized in two main groups: **Single-select** and **Multi-select** dropdowns. Both of them have up to 7 states, including: default, on-hover, on-focus, filled-out, disabled, hint and error. All input types have the height size of 40px and they come in 5 different width sizes.

**Note:** All CSS shown is for guiding purposes, it's not absolute.

#### Spacing guidelines

* Based on their width size, dropdown list menus are categorized in 5 groups: **XL**, **L**, **M**, **S** and **XS**.
* Dropdowns are mostly used in forms so the group sizes are designed to fit them perfectly.
* In forms, the total width of the dropdowns per row must be 380px, therefore use width sizes depending on how much dropdowns are needed in a single row.
* The margin between dropdowns in a single row must be 16px.

![](/assets/atoms/dropdowns-sizes.png)

```
/* Dropdown XL */
width: 380px;

/* Dropdown L */
width: 281px;

/* Dropdown M */
width: 182px;

/* Dropdown S */
width: 116px;

/* Dropdown XS */
width: 83px;
```

### Single-select

* Used when there are multiple choices, but only one option can be selected.
* Consider using radio buttons, as opposed to a select if there are only a couple/few options, or a simple either/or choice.
* A select also uses less space than a group of radio buttons — something to consider if your form is long, or space is limited.

##### Classic list

![](/assets/atoms/dropdowns-classic-single-select-states.png)

