# Basic

__Description__: Should be able to use all CSS properties within a ctr instance.


<div data-size="125" class="code-cont">
    <div class="example1 code">
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


<div data-size="125"></div>
```styl
ctr('.test', {
  width: 200px
  future-property: 100%
})
```

```css
.test {
  width: 200px;
  future-property: 100%;
}
```



__Notes__

+ The `future-property` is to demonstrate that ctr can handle anything the future has to hold


<div class="end"></div>




