# Blog
本blog主要用于记录和总结前端常用知识和相关内容的深入理解，帮助自己进行前端知识体系的构建，形成技术沉淀。也方便今后查询。如果很幸运的对你有一点帮助，那我真的很开心😊。

## 🍎BASIC

### JAVACRIPT

#### 核心
I. 对象

对象是js中最常见的也是最重要的部分。

js中对象创建除了使用字面量和`Object.create`，最常用的还是`new`。使用`new`创建对象的基本过程如下:

- 生成一个新对象
- 设置原型链
- 绑定this
- 返回该对象（如果构造函数本身有返回值，则返回那个值）

使用代码实现
```javascript
function createObject(Con, ...args) {
 var t = {};
 t.__proto__ = Con.prototype;
 t.constructor = Con;
 Con.apply(t, args);
 return t;
}
```

原型
构造函数
执行上下文
 - 变量对象
 - 作用域链
 - This


#### 对象拷贝
#### 继承方式
#### 类型
#### 模块化
#### AST
#### BABEL编译过程
#### 防抖和节流
#### ES6/ES7

### CSS
#### 基础知识
#### 技巧方面

## 🍐BROWSER
### 组成部分
### 渲染
### 核心机制
### 跨标签页通信
### 内存泄漏
### 安全

## 🍑NETWORK
### HTTP
#### 分类
#### 常见状态码
#### HTTP缓存

### 跨域
#### CORS
#### JSONP

### WEBSOCKET

## 🍒OPTIMIZATION
