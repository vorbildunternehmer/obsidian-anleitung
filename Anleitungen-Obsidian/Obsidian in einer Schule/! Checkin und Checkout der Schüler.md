Checkin & Checkout der Schüler
===

```dataview
table Klasse, Checkin, Checkout
 from ""
 where Schüler and file.folder != "templates"
 sort Schüler asc
```