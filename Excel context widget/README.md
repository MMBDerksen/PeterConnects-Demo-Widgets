# PeterConnects-Excel-Context-Widget

Lookup of an Excel record based on call/contact properties.

For a live example, use this URL:\
https://delivery.peterconnects.com/demo-widgets/excel-context-widget.html?src=QueueNumbers.xlsx&matchwith=Queue%20number&match=+31850520332

URL Parameters:
- src        Excel source document (required)
- match      The value to match (required)
- matchwith  column name to compare against in the Excel document (optional, default is first column)

## Note on Excel document
If you want to read the Excel document from a different damain as the domain where the widget page is hosted, make set up a CORS policy.
Otherwise, the web page will not be able to read the Excel document.

