## 抽象工厂模式

### 使用场景

1. 客户端不需要知道它所创建的对象的类。
2. 客户端可以通过子类来指定创建对应的对象，每个工厂都可以产生多种不同类型的对象。

### 优缺点
* 优点
  * 相比于简单工厂模式，不需要改动原有代码。

* 缺点
  * 扩展复杂，需要增加抽象的Creator代码，也需要增加具体的实现代码。

### 示例
* [工厂模式的PHP实现](https://github.com/suvllian/learning/tree/master/design-patterns/creational-patterns/factory-method)

### 文档