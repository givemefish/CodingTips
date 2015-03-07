# Coding Tips

### Debugging
  
 * console.group() & console.groupEnd() 可以在console pane中加入一段區間, 可將console.log的內容記錄在其中, 以便和其他log區分
 * console.groupCollapsed() 可以創建收合的區間
 * console.group() & console.groupCollapsed() 可為巢狀 [[參考連結](https://blog.mariusschulz.com/2014/11/25/advanced-javascript-logging-using-console-group) ]
 * console.table() 可列出陣列訊息, Chrome預設會在前面多加一段index 
 ```javascript
 var languages = [
    { name: "JavaScript", fileExtension: ".js" },
    { name: "TypeScript", fileExtension: ".ts" },
    { name: "CoffeeScript", fileExtension: ".coffee" }
];
console.table(languages);
```
 * console.table() 亦可傳入物件, 此時前面的index欄會變成物件的屬件
