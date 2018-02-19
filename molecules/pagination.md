# Pagination

Pagination is displayed below tables when there are a significant number of table rows.

**Note: **All CSS shown is for guiding purposes, it's not absolute.

#### General guidelines

* Pagination is centrally aligned.
* If the user is on the first page of table results, the ‘Back’ button is disabled. If they are on the last page of table results, ‘Next’ is disabled.
* If ≤ 7 pages, no need for truncating the pagination \(adding "..."\).
* An ellipses \(...\) is shown between non-consecutive pages.
* The first and last page should always be visible.
* The previous two and the next two pages should always be visible.
* The max limit of the visible pages should be 7 only in cases when there are two pages before and two pages after plus the first and the last page \(example at the very bottom of the image below\).
* [Neutral button](//atoms/buttons.html#neutral-buttons) style with the height of 32px is applied to the Next and Back actions.

![](/assets/molecules/pagination-guidlines.png)

#### Spacing guidelines {#spacing-guidelines}

* The margin between pagination elements is always 8px.
* The left and right padding of the pagination elements is always 16px.
* Ellipses use following CSS: `font-family: Open Sans; font-weight: Semibold; font-size: 15px; margin: 0 4px 0 4px;`

![](/assets/molecules/pagination-spacing.png)

### Page numbers

Page numbers have 4 different states: Default, On-hover, On-focus and Active. The height of the number boxes is always 32px.

![](/assets/molecules/pagination-page-numbers.png)

```
/* Default */
background: $S100;
height: 32px;
border: 1px solid $S400;
border-radius: 3px;
margin: 0 4px 0 4px;
padding: 0 12px 0 12px;
font-family: Open Sans;
font-weight: Semibold;
font-size: 13px;
color: $B200;

/* On hover */
box-shadow: 1px 1px 4px 0 $S300;

/* On focus */
border: 1px solid $G200;
box-shadow: 1px 1px 4px 0 $G200;

/* Active */
background: $G300;
border: none;
color: $S100;
```



