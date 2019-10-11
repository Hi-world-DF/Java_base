## interface
接口和类和相似，但有区别
*****
##### 接口与类相似点：
* 一个接口可以有多个方法
* 接口文件保存在 .java 结尾的文件中，文件名使用接口名
* 接口的字节码文件保存在 .class 结尾的文件中
* 接口相应的字节码文件必须在与包名称相匹配的目录结构中

##### 接口与类区别：
- 接口不能用于实例化对象
- 接口没有构造方法
- 接口中所有的方法必须是抽象方法
- 接口不能包含成员变量，除了 static 和 final 变量
- 接口不是被类继承了，而是要被类实现
- 接口支持多继承

************
例子：

    /* 文件名 : Animal.java */
    interface Animal {
       public void eat();
       public void travel();
    }

接口的实现：  
> 当类实现接口的时候，类要实现接口中所有的方法。否则，类必须声明为抽象的类。  
> 类使用implements关键字实现接口。在类声明中，Implements关键字放在class声明后面。

    /* 文件名 : MammalInt.java */
    public class MammalInt implements Animal{
     
       public void eat(){
      		System.out.println("Mammal eats");
       }
     
       public void travel(){
      		System.out.println("Mammal travels");
       } 
     
       public int noOfLegs(){
      		return 0;
       }
     
       public static void main(String args[]){
      		MammalInt m = new MammalInt();
      		m.eat();
      		m.travel();
       }
    }

运行结果：

    Mammal eats
    Mammal travels
