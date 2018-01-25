# Javascript selector 
JavaScript has 2 types of selector 
* scalar selector will return single element
* composite selector will return array of elements.  

some elements are unique in html page. like head, body, title, id etc. In this case we will get single element from selector. However in case of tag and class we will get array of element since they can be occur more than one times in html page. So whenever we found array of elements we have to extract single element from array of elements to change them.

## 5 css selector where first 4 is supported by querySelector and querySelectorAll      

* tag (`body`)
* id (`#hello`)
* class (`.hello`)
* attribute(`[id='hello']`)
* pseudo(`a:hover`)   


### some selector which will give us single element 

~~~js
document.body
document.head
document.getElementById('some_id')
document.querySelector('any of first 4 css selector from state above list')
~~~

### some selector which will give us array of elements

~~~js
document.getElementsByClassName('html class')
document.getElementsByTagName('htmltag')
document.querySelectorAll('any of first 4 css selector from state above list')
~~~

## modern javascript selector `querySelector` and `querySelectorAll` 


#### document.querySelector('css selector')
its a scaler type selector in js dom. it will return single element which can be change directly. It will take css selector(first 4 from state above css selector list) as argument

#### document.querySelectorAll('css selector');
its a composite type selector in js dom. It will return array of elements. So in order to change a element we have to extract single element by their index. It will take css selector(first 4 from state above css selector list) as argument






