# 简介

链式延迟执行函数

# 详解

#### w()

等待队列

#### r()

执行队列函数

#### 初始化

``` javacript
dcDelay.w(100).r(function(){
     console.log("1")
}).w(700).r(function(){
     console.log("2")
}).w(3000).r(function(){
     console.log("3")
}).w(40).r(function(){
     console.log("4")
}).w(1000).r(function(){
     console.log("5")
}).w(800).r(function(){
     console.log("6")
})
```
