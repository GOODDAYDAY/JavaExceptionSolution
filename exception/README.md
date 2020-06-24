### README

* 请用模板进行记录，如果嫌模板麻烦，可以提交issue，我们来进行记录。也可以提出更合适的模板，我们共同进步。
* 如果情形相差无几，可以放在一个solution里，大家查找方便，看的简单是最终目的。

#### 报错信息格式模板

* 类型
    * exception Reference
    * 作为关键字的一种没有则不填


* 关键字
    * introduction
    * ...

* 文件名
    * `类型`^o^`关键字一`^o^`关键字二`.md

* 报错情形描述
    * 一、`解决方案`(跳转) - 描述
        * 报错首行
            * 将特殊业务字段通用化，如userName -> xxxx
        * 具体情境(自由发挥)


#### 报错信息格式样例


* 文件名
    * java.lang.NullPointer^o^空指针^o^未初始化.md

* 类型
    * java.lang.NullPointer

* 关键字
    * 空指针
    * 未初始化

* 报错情形描述
    * 一、[解决方案](../sulotion/javaBasic/java.lang.NullPointer^o^空指针^o^未初始化^w^solution1.md) - 调用对象方法时报错
        * 代码片段
        
            ```java
            Node node = null;
            node.doSomething();
            ```

        * 报错首行信息

