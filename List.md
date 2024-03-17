
## All cards

```dataview
table Author, Cover as Cover
from "Cards"
sort file.name asc
```


## Cards by Category

```dataview
table rows.file.link as Book
from "Cards"
group by Category
sort Category
```