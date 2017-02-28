
# DocumentSelectionChangedEventArgs.document property
Gets a  **Document** object that represents the document that raised the **SelectionChanged** event.

|||
|:-----|:-----|
|**Hosts:**|Excel, Word|
|**Added in**|1.1|




```js
var myDoc = eventArgsObj.document;
```


## Return Value

A [Document](../../reference/shared/document.md) object that represents the document that raised the [SelectionChanged](../../reference/shared/document.selectionchanged.event.md) event.


## Support details


A capital Y in the following matrix indicates that this method is supported in the corresponding Office host application. An empty cell indicates that the Office host application doesn't support this method.

For more information about Office host application and server requirements, see [Requirements for running Office Add-ins](../../docs/overview/requirements-for-running-office-add-ins.md).


**Supported hosts, by platform**


||**Office for Windows desktop**|**Office Online (in browser)**|**Office for iPad**|
|:-----|:-----|:-----|:-----|
|**Excel**|Y|Y|Y|
|**Word**|Y||Y|

|||
|:-----|:-----|
|**Minimum permission level**|[Restricted](../../docs/develop/requesting-permissions-for-api-use-in-content-and-task-pane-add-ins.md)|
|**Add-in types**|Content, task pane|
|**Library**|Office.js|
|**Namespace**|Office|

## Support history



****


|**Version**|**Changes**|
|:-----|:-----|
|1.1|Added support for Excel, PowerPoint, and Word in Office for iPad.|
|1.0|Introduced|