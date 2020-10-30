# To get total page count
Write the script under layout:ready event
```javascript
this.rawValue = xfa.layout.pageCount();
```
# To get current page number
Write the script under layout:ready event
```javascript
if(xfa.layout.page(this) == 1){
// do some stuff on first page
}else{
// do some magical on other pages
}
```
