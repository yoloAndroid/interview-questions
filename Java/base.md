####  == 和 equals 的区别？  
* == 是运算符，equals 是 Object 类的方法
* 基本类型 == 比较的是值是否相同,引用类型 == 比较的是引用是否相同
* 未重写时 equals 等价于 ==,覆写 equals 是追求两个对象在逻辑上的相等（值相等、内容相等）。

	>Java 语言里 equals 存在的目的是交给开发者去覆写的，让开发者自己去根据业务规则的不同，定义满足什么条件的两个Object是equal的。

