# To get total page count
```javascrpt
this.rawValue = xfa.layout.pageCount();
```
# To get current page number
```javascrpt
if(xfa.layout.page(this) == 1){
// do some stuff on first page
}else{
// do some magical on other pages
}
```
