Physijs 汉化
=======
#### three.js的物理引擎插件 [three.js](https://github.com/soulsheng/three.js)

three.js最大的特点就是简单易用，物理动力学插件Physics继承这个优点，只需要<a href="https://github.com/soulsheng/Physijs/wiki/Basic-Setup">六步</a>就能让你的三维场景活起来。

#### 物理插件功能原理
插件在一个新的线程里面运行，不会占用渲染时间，所以避免影响原来的渲染效率。

#### 这个插件能用来做什么
但愿你熟悉three.js，并且想加入物理引擎功能，这个插件非常适合你. 不用改变原有设计-简单地加入一些额外的碰撞体就能获取一个动态的模拟环境。

### 例子
[![rigid bodies](http://chandlerprall.github.com/Physijs/examples/body.jpg)](http://chandlerprall.github.com/Physijs/examples/body.html)
[![collisions](http://chandlerprall.github.com/Physijs/examples/collisions.jpg)](http://chandlerprall.github.com/Physijs/examples/collisions.html)
[![compound shapes](http://chandlerprall.github.com/Physijs/examples/compound.jpg)](http://chandlerprall.github.com/Physijs/examples/compound.html)
[![all shapes](http://chandlerprall.github.com/Physijs/examples/shapes.jpg)](http://chandlerprall.github.com/Physijs/examples/shapes.html)
[![jenga](http://chandlerprall.github.com/Physijs/examples/jenga.jpg)](http://chandlerprall.github.com/Physijs/examples/jenga.html)

### 特性
* 支持 [多种模型](https://github.com/soulsheng/Physijs/wiki/Basic-Shapes), 以及地形.
* 材质支持摩擦和弹性
* 集成碰撞检测
* 模型分组嵌套
* 旋转支持欧拉角和四元数两种模式
* 无缝集成three.js

### 展望
* 进一步优化
* 支持凹面拆分