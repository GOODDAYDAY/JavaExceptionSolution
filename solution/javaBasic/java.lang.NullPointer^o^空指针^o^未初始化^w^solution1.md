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



