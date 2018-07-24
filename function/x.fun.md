## 创建立即运行的函数

* 运行原因： 符号 `!` 将这个函数当成运算获取 `boolean` 型使用

```js
;!function () {
    alert()
}()
```

* 运行原因： 符号 `()` 将函数包裹，使函数达到可以运行的状态
```js
(function () {
    alert()
})()
```
