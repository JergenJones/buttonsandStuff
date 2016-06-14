# Multiple Properties With Commas

__Description__: If a property has multiple parts and its parts are separated by a comma `,` as sometimes is the case with `box-shadow` the user can still use said value although it must be wrapped in a `string`.


<div data-size="100" class="code-cont">
    <div class="example3 code">
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


<div data-size="100"></div>
```styl
ctr('.test', {
  box-shadow: '3.3em 0em rgba(255, 0, 0, 0.1), 5.71188em 1.00716em rgba(255, 43, 0, 0.6), 5.45022em 1.98372em rgba(255, 85, 0, 0.6), 2.85788em 1.65em #ff8000, 4.44306em 3.72817em rgba(255, 170, 0, 0.9), 3.72817em 4.44306em #ffd500, 1.65em 2.85788em rgba(255, 255, 0, 0.7), 1.98372em 5.45022em rgba(213, 255, 0, 0.8)'
})
```

```css
.test {
  box-shadow: 3.3em 0em rgba(255,0,0,0.1), 5.71188em 1.00716em rgba(255,43,0,0.6), 5.45022em 1.98372em rgba(255,85,0,0.6), 2.85788em 1.65em #ff8000, 4.44306em 3.72817em rgba(255,170,0,0.9), 3.72817em 4.44306em #ffd500, 1.65em 2.85788em rgba(255,255,0,0.7), 1.98372em 5.45022em rgba(213,255,0,0.8);
}
```


<div class="end-last"></div>
