## Font Sizes
How to use:

`<p class="font-xxx">some text</p>`

xxx: can be any number b/w **8-50**

```
<p class="font-14">some text</p>
```

Add a number between the above range and get desired font-size for text elements.

---
## Input Placeholder
How to use:

```
.input-field,
textarea{
    @include placeholder{
        color:red;
        font-size:12px;
    }
}
```

Suppose we have to change the styles of placeholder in our input field, just include **Placeholder** mixin in the input field
and change the properties of placeholder accordingly.