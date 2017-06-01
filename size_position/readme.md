# 关于位置和尺寸的属性
## 获取具有滚动条元素的位置属性
    scrollTop,scrollLeft 具有滚动条的元素在滚动的时候，他的内部元素超出该元素顶部，或是左边的距离
## 事件对象位置属性
    clientX,clientY  相对于浏览器窗口的位置
    screenX,screenY 相对于屏幕的位置
    offsetX,offsetY  IE 
    layerX,layerY   　FF  
    相对于事件源
## 固定定位
    1 css hack  
        解决不同浏览器针对css差异的一些方法   IE6不认识固定定位
    2 css 表达式
        expression()    
## 透明度
    IE：filter:alpha(opacity=40) FF: opacity:.4;


## 运动框架基础
    1   核心函数 setInterval(回调函数，间隔时间)
    2   js 是单线程 异步机制  定时器，dom事件属于异步
    3   运动元素，开始值，变化值，最终值，结束条件
