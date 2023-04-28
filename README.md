# JSDatasetProperty
Javascript Dataset property for boolean DOM 


```HTML

<div id="dataSetID" data-name="niel" data-expert="javascript">
</div>

```

```JS

 let dataObject = document.getElementById('dataSetID');
 
 console.log(dataObject.dataset);
 
 // console result 
 DOMSTringMap {
   name: "niel"
   expert : "javascript"
 }
 __proto__ : DOMStringMap
 
```
