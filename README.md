# To get total page count
```javascript
this.rawValue = xfa.layout.pageCount();
```
# To get current page number
```javascript
if(xfa.layout.page(this) == 1){
// do some stuff on first page
}else{
// do some magical on other pages
}
```
