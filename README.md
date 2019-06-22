# vue-analysis
Take notes for Vue

### 数据双向绑定
Vue实现数据双向绑定主要是：采用**数据劫持结合发布者-订阅者模式**的方式

首先一定要知道**Object.defineProperty()方法**

Object.defineProperty()方法会直接在一个对象上**定义一个新属性**，或者**修改一个对象的现有属性**，并返回这个对象。

> Object.defineProperty(obj, prop, descriptor) 

##### 参数介绍
```
obj: 要进行定义属性的对象
prop: 要定义或修改的属性名称
descriptor: 将被定义或修改的属性描述符
```

如需了解详细descriptor参数及方法描述 [参考MDN](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)

[简易双向绑定](https://github.com/CrankySimba/vue-analysis/tree/master/数据双向绑定)

### TODO
- 理解数据劫持结合发布者-订阅者模式






