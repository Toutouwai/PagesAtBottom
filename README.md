# Pages At Bottom

A module for ProcessWire CMS/CMF. Keeps selected pages at the bottom of their siblings.

* A "bottom page" will stay at the bottom even if it is drag-sorted to a different location or another page is drag-sorted below it (after Page List is refreshed the bottom page will still be at the bottom).

* Newly added sibling pages will not appear below a bottom page.

* The module also prevents the API methods [$pages->sort()](https://processwire.com/api/ref/pages/sort/) and [$pages->insertAfter()](https://processwire.com/api/ref/pages/insert-after/) from affecting the position of bottom pages.

## Why?

Because you want some pages to always be at the bottom of their siblings for one reason or another. And [someone requested it](https://processwire.com/talk/topic/20504-make-page-stick-to-the-bottom-of-the-page-tree/). :simple_smile:

## Usage

[Install](http://modules.processwire.com/install-uninstall/) the Pages At Bottom module.

Select one or more pages to keep at the bottom of their siblings.
