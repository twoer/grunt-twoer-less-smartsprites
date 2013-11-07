grunt-contrib-smartsprite
=========================


> 本程序完全 Copy https://github.com/gruntjs/grunt-contrib-less

> 唯一区别就是原程序在编译 Less 时，会破坏 https://github.com/carrotsearch/smartsprites 特定注释语法 `background-image:url('@{bg-srpite-url}bg-step.png'); /** sprite-ref: bg-step;*/`，导致 smartsprites 无法正确解析运行，so......


## 使用方法：
> 完全同 https://github.com/gruntjs/grunt-contrib-less
> 唯一区别就是增加了一个 `smartSpriteTag` 参数
```js
//grunt smartsprite
smartsprite: 
{
    options: 
    {
        smartSpriteTag : true,
        ......
    }
}
```

#### smartSpriteTag
Type: `Boolean`  
如果为 `True` 会在 Less 编译时，保存 smartsprites 特定注释语法，否则不做任何处理  



## 感谢：
* Waitcat


## 最后
* 其实我已经 pull request 到 https://github.com/gruntjs/grunt-contrib-less ，但是其作者不同意合并！
* 新手，程序难免有瑕疵，望大家多包涵，多斧正！


 
















