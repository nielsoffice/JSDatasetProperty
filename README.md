# JSDatasetProperty [ Custom Data HTML Attributes ]
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

```JS
// Select ELement by Attribute
var element = document.querySelector('[data-name="niel"]');

console.log(element);

// Console.log Result 
<div id="dataSetID" data-name="niel" data-expert="javascript"></div>

```

<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/dataset
<br /> 
<br /> Attributes Condition estatement
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/attributes
<br /> Get Attribute
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute
<br /> Set Attribute
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute
<br /> Boolean | hasAttributes
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/hasAttribute
<br /> removeAttributes
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/removeAttribute
<br /> removeAttributesNode
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/removeAttributeNode


