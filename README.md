# JS Tag Insert To Target Element function
JavaScript Insert Tag in other target element using tag ID JS Function. ex. insertAfter(); of jQuery.

<br /> Element.insertAdjacentElement();
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentElement
<br /> 
```HTML

 // insertAdjacentElement(position, element);
 
Parameters
<!-- position
A string representing the position relative to the targetElement; must match (case-insensitively) one of the following strings:
-->
'beforebegin': Before the targetElement itself.
'afterbegin': Just inside the targetElement, before its first child.
'beforeend': Just inside the targetElement, after its last child.
'afterend': After the targetElement itself.
<!-- Element
The element to be inserted into the tree.
-->

ex. 
<!-- beforebegin -->
<p>
  <!-- afterbegin -->
  foo
  <!-- beforeend -->
</p>
<!-- afterend -->
```
<br /> Element.insertAdjacentHTML();
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML

<br /> Element.insertAdjacentText();
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentText

<br /> Element.after();
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/after

<br /> Element.prepend()
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/prepend

<br /> Element.append()
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/append

Demo : https://github.com/nielsoffice/JSScriptLoadAfterBody
