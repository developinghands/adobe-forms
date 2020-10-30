# To get total page count
To get the total page count in Sap adobe forms, write the below script under layout:ready event
```javascript
this.rawValue = xfa.layout.pageCount();
```
# To get current page number
To get the current page number in SAP adobe forms, write the below script under layout:ready event
```javascript
if(xfa.layout.page(this) == 1){
// do some stuff on first page
}else{
// do some magical on other pages
}
```
Source: [javascript Examples](https://help.adobe.com/en_US/livecycle/10.0/DesignerScriptingRef/WS92d06802c76abadb-3e14850712a151d270d-7ffa.html)
Source: [javascript Functions](https://help.adobe.com/en_US/livecycle/10.0/DesignerScriptingBasics/WS92d06802c76abadb39b5236b129f6917ab6-7fd5.html)
