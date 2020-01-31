# Coding Tips

## Debugging

### Browser
 * console.group("name") & console.groupEnd() 可以在console pane中加入一段區間, 將console.log的內容記錄在其中
 * console.groupCollapsed("name") 和console.group("name")作用相似, 但它可以創建收合的區間
 * console.group() & console.groupCollapsed() 可為巢狀 [[參考連結](https://blog.mariusschulz.com/2014/11/25/advanced-javascript-logging-using-console-group) ]
 * console.table(array) 可列出陣列訊息, Chrome預設會在前面多加一段index  
 * console.table(object) 亦可傳入物件, 此時前面的index欄會變成物件的屬件, 此時亦可指定欄位來顯示, 例如```console.table(languages, ["name", "paradigm"]);```[[參考連結](https://blog.mariusschulz.com/2013/11/13/advanced-javascript-debugging-with-consoletable)]
 * console.time("name")和console.timeEnd("name")可以計算夾在中間的javascript花了多久的時間執行 [[參考連結](https://blog.mariusschulz.com/2013/11/22/measuring-execution-times-in-javascript-with-consoletime)] 
 
 
### Web API

 * 在ASP.NET Web API中, 如果要看更詳細的錯誤訊息, 使用CustomerErrors沒有用, 必須指定```GlobalConfiguration.Configuration.IncludeErrorDetailPolicy 
    = errorDetailPolicy;```[[參考連結](http://lostechies.com/jimmybogard/2012/04/18/custom-errors-and-error-detail-policy-in-asp-net-web-api/)]
 * [HTTP API 设计指南](https://github.com/ZhangBohan/http-api-design-ZH_CN)
 * [跟著Github學習Restful HTTP API設計](http://www.codeceo.com/article/learn-restful-http-api-design.html)
 * [ASP.NET Core WebAPI版本設計 - 使用Swagger](https://dejanstojanovic.net/aspnet/2018/november/setting-up-swagger-to-support-versioned-api-endpoints-in-aspnet-core/?utm_source=csharpdigest&utm_medium=rss&utm_campaign=featured)

### ASP.NET MVC
 
 * [擴展ASP.NET MVC](http://www.codeceo.com/article/8-tips-aspnet-mvc.html)
 
 ### ASP.NET CORE
 
 * [Health Check UI](https://marcus116.blogspot.com/2019/05/netcore-aspnet-core-health-check-ui.html)

### CSS

 * [CSS scroll-behavior和JS scrollIntoView让页面滚动平滑](https://www.zhangxinxu.com/wordpress/2018/10/scroll-behavior-scrollintoview-%e5%b9%b3%e6%bb%91%e6%bb%9a%e5%8a%a8/)
 * [Min and Max Width/Height in CSS](https://ishadeed.com/article/min-max-css/)
