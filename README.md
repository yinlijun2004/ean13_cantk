# ean13_cantk
a tiny tool to gen13 code on cantk

Thanks to [jamesliu96](https://github.com/jamesliu96/ean13)

Intergration Step:

### Copy ean13_cantk.js code in to ide.

###
```javascript
this.genCode = function(num) {
    var ean = new EAN13(num);
    if(ean.bincode){
        ean.cantkDraw(this.image);
    }
}

this.genCode(this.edit.getValue());
```
