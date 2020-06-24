### README

* 请用模板进行记录，如果嫌模板麻烦，可以提交issue，我们来进行记录。也可以提出更合适的模板，我们共同进步。
* 如果情形相差无几，可以放在一个solution里，大家查找方便，看的简单是最终目的。

#### 解决方案格式模板

* 文件名
    * `类型`^o^`关键字一`^o^`关键字二`^w^`solution"N"`.md

* 类型
    * exception Reference
    * 作为关键字的一种没有则不填


* 关键字
    * introduction
    * ...


* 报错情形描述
    * 对应错误信息的描述

* 解决方案
  * 自由发挥

* [返回首页](https://github.com/GOODDAYDAY/JavaExceptionSolution)

#### 解决方案格式样例

* 文件名
    * java.lang.NullPointer^o^空指针^o^未初始化^w^solution1.md

* 类型
    * java.lang.NullPointer

* 关键字
    * 空指针
    * 未初始化

* 报错情形描述
    * 调用对象方法时报错

* 解决方案


  * 1.应在调用对象前保证其初始化完毕

  * 2.在调用对象前先判断是否为null

    ```java
    Node node = getNode();
    if(null == node){
        // do something
        doNullNode();
    }else{
        doNode();
    }

    ```

* [返回首页](https://github.com/GOODDAYDAY/JavaExceptionSolution)



