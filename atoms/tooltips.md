# Tooltips {#tooltips}

Tooltips can be attached to any element. When you hover the element with your mouse, the title attribute is displayed in a little box next to the element. Tooltips are useful for things like form elements and tables, to show additional or helpful information.

**Note: **All CSS shown is for guiding purposes and it's not absolute.

#### General guidelines {#general-guidelines}

* Use tooltip direction depending on the position of the element that is hovered.

#### Spacing guidelines

* There is a padding of 16px on all sides.
* The height line of the tooltip text is 16px.
* The arrow indicator has 16x8px \(8x16px\) size.
* The max width of the tooltip should be 376px \(which is known as 'XL' size for Input types or Dropdowns\).
* Tooltips can be displayed in multiple lines if the text is long.

![](/assets/atoms/tooltips-sizes.png)

```
/* Tooltip base */
max-width: 376px;
background-color: $B400;
padding: 16px;
border-radius: 3px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 12px;
text-align: left;
line-height: 16px;
color: $S500;

/* Tooltip triangle left and right */
width: 8px;
height: 16px;

/* Tooltip triangle up and down */
width: 16px;
height: 8px;
```



