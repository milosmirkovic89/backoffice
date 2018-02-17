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

![](/assets/molecules/pagination-guidlines.png)

#### Spacing guidelines {#spacing-guidelines}

* The margin between pagination elements is always 8px.
* The left and right padding of the pagination elements is always 16px.

![](/assets/molecules/pagination-spacing.png)

