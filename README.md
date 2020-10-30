# To get total page count
To get the total page count in Sap adobe forms, write the below script under layout:ready event
```javascript
this.rawValue = xfa.layout.pageCount();
```
# To get current page number
To get the current page number in Sap adobe forms, write the below script under layout:ready event
```javascript
if(xfa.layout.page(this) == 1){
// do some stuff on first page
}else{
// do some magical on other pages
}
```
