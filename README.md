# flextable
Example `flexbox` based grid with a comparable `display:table` fallback

## Caveat
This is solely for the purpose of investigation.
The goal of this repo is to illustrate the simplest flexbox grid with the simplest fallback.
( We all know how subjective the word simple is )

I am by no means saying this is a perfect solution, just hoping seeing this might spark some rush of brilliance by someone smarter than I.

Normally I would never use descendant selectors like:
```
.grid-gutters > .grid-row > .grid-column
```
Or worse
```
.no-flexbox .grid-gutters > .grid-row > .grid-colum
```
but, [modernizr](http://v3.modernizr.com) works this way and this approach requires the least amount of additional classes in the DOM.
Again it is an illustration of what is required to make a flexbox based grid fallback to  table based one.

Discuss.
