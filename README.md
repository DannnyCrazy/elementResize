# elementResize
开发过程中经常遇到的一个问题就是如何监听一个元素的size变化。 
比如我用canvas绘制了一个chart，当canvas的size发生变化的时候，需要重新绘制里面的内容，这个时候就需要监听resize事件做处理。
window上虽然可以添加resize事件监听，但这并不能满足我们的需求，因为很多时候，div的size发生了变化，但是window的size并没有改变。 

# 使用
1. 导入eleRsize.js
2. 添加监听事件
  ```
  eleResize.on(element, listener)
  ```
3. 移除监听事件
  ```
  eleResize.off(element, listener)
  ```