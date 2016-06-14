# Multiple Properties

__Description__: Should be able to use all CSS properties within a ctr instance, including properties such as `box-shadow` which have multiple values. The user should be able to use string values interchangeably.


<div data-size="325" class="code-cont">
    <div class="example2 code">
        <div class="loader"></div>
        <div class="code-wrap">
            <textarea id="stylus"></textarea>
            <textarea id="css"></textarea>
            <div class="edit-code">
                <span>Edit</span>
            </div>
        </div>
    </div>
</div>


<div data-size="325"></div>
```styl
ctr('.test', {
  background: linear-gradient(135deg, rgba(183,222,237,0.9) 0%,rgba(113,206,239,0.9) 50%,rgba(33,180,226,0.9) 51%,rgba(183,222,237,0.9) 100%)
  box-shadow: 0px 3px 8px 1px rgba(0,0,0,0.75)
  text-shadow: 2px 1px 2px rgba(150, 150, 150, 0.9)
})

//string wrapped properties
ctr('.test-string', {
  background: 'linear-gradient(135deg, rgba(183,222,237,0.9) 0%,rgba(113,206,239,0.9) 50%,rgba(33,180,226,0.9) 51%,rgba(183,222,237,0.9) 100%)'
  box-shadow: '0px 3px 8px 1px rgba(0,0,0,0.75)'
  text-shadow: '2px 1px 2px rgba(150, 150, 150, 0.9)'
})
```

```css
.test {
  box-shadow: 0px 3px 8px 1px rgba(0,0,0,0.75);
  text-shadow: 2px 1px 2px rgba(150,150,150,0.9);
  background: linear-gradient(135deg, rgba(183,222,237,0.9) 0%, rgba(113,206,239,0.9) 50%, rgba(33,180,226,0.9) 51%, rgba(183,222,237,0.9) 100%);
}
.test-string {
  box-shadow: 0px 3px 8px 1px rgba(0,0,0,0.75);
  text-shadow: 2px 1px 2px rgba(150,150,150,0.9);
  background: linear-gradient(135deg, rgba(183,222,237,0.9) 0%, rgba(113,206,239,0.9) 50%, rgba(33,180,226,0.9) 51%, rgba(183,222,237,0.9) 100%);
}
```


<!-- This note has periods at the ends of both sentences so I changed that. Here's the original if we prefer to keep it as was: 

+ If you have a property value like `box-shadow` which has multiple parts separated by `,` then you must wrap the value in a string. Look at the test below.
 -->
__Notes__

+ If you have a property value like `box-shadow` which has multiple parts separated by `,` then you must wrap the value in a string (see test below)



<div class="end"></div>
