# knockout-datatables
A simple Knockout binding for Datatables. This project is not under active development and has not been extensively tested.

## Dependencies
[JQuery](https://jquery.com/download/), [DataTables](https://datatables.net/download/index) and [Knockout](http://knockoutjs.com/downloads/index.html).

## Usage
Examples to be added

A [DataTables options object](https://datatables.net/reference/option/) must be passed to the binding with 3 required properties: 

  1. ["data"](https://datatables.net/reference/option/data) property as a json or knockout object array
  
  2. ["columns"](https://datatables.net/reference/option/columns) property, each containing a ["title"](https://datatables.net/reference/option/columns.title) and ["data"](https://datatables.net/reference/option/columns.data) and,
  
  3. A "uniqueKey" property (not a part of DataTables) that is the property name for a unique value in each data object. It is fine to omit this if you don't plan to delete data from the datasource. 
  
Also, this binding does not support the ajax option of DataTables because all data retreival and persistance should be handled by Knockout.
