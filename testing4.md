---
title: Applied Filters
slug: applied-filters
---

The Applied Filters directive keeps track of all filter options checked on a sidebar of a page that presents a list of filtered items. It shows each filter applied in a list and provides a "x" button next to the filter name that when clicked will de-select that filter and update the results shown. The list of applied filters is shown inside of an accordion component that allows the user to collapse and expand the widget to hide and show the list of applied filters. It is expanded by default.


## HTML

```
<ag-applied-filters data-applied-filters="moreSearch" data-remove-filter-callback="changeFilter"> 
```
## OPTIONS

| Options                  | Type         	   | Default/Values      |   Description                                                                                                                    |
| ------------------------ | :---------------: | :-----------------: | :------------------------------------------------------------------------------------------------------------------------------- |
| appliedFilters           | Object            | No default value    | Key/value pair map that contains applied filter values   																	    |
| removeFilterCallback     | Object            | No default value    | Function that is called when a user clicks the "x" button to remove a filter from the applied filters list. This allows custom logic to be executed after a filter is removed from the list.                                                                    |
