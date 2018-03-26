# Forms

#### General guidelines {#spacing-guidelines}

* On desktop resolutions labels and inputs are displayed inline.

#### Spacing guidelines {#spacing-guidelines}

* Form section has a padding of 32px.
* The height of rows is 40px.
* The padding between rows is 16px.
* The padding between the last data row and action buttons at the bottom is 32px. 

![](/assets/organisms/forms-spacing.png)

```
/* Form section */
padding: 32px;
```

---

![](/assets/organisms/forms-sizing.png)

```
/* Row */
hight: 40px;
```

---

### Labels

Labels are used inline before all text inputs, text areas and drop-downs. For elements that are a required field, the label or legend should include an asterisk `*` after the label/legend, separated by a space \(`e.g. First name *`\). The max width of labels is 380px.

![](/assets/organisms/forms-labels-sizing.png)

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

---



