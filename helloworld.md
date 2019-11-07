# 第一个入门程序Hello World

	//编写一个类名：helloWorld的类
    class helloWorld{
 
    	//java程序的入口main方法
    　　public static void main(String ags[]){
    
    	   //打印输出一句 Hello World!
    　　　　System.out.println("Hello World!");
    
    　　}
    }


## 程序详解

### 一、类
例如上面程序中的`helloWorld`就是一个类，用`class`关键词声明。

`helloWorld`类中有`main()`方法，说明这是个java应用程序，通过JVM(Java虚拟机)直接启动运行的程序。

### 二、main()方法

在Java中，`main()`方法是Java应用程序的入口方法，格式相对比较固定，即程序在运行时，第一个执行的方法就是`main()`方法，这个方法很特殊，首先方法的名字必须是`main`，其次方法必须是`public` `static` `void` 类型的，且方法必须接收一个字符串数组的参数等等。

### 三、输出print、printf、println

print\println\printf的区别


print将它的参数显示在命令窗口，并将输出光标定位在所显示的最后一个字符之后。


println 将它的参数显示在命令窗口，并在结尾加上换行符，将输出光标定位在下一行的开始。


printf是格式化输出的形式。

