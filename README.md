# zuoye4
实验目的：
掌握Java中抽象类和抽象方法的定义； 
掌握Java中接口的定义，熟练掌握接口的定义形式以及接口的实现方法
了解异常的使用方法，并在程序中根据输入情况做异常处理
实验要求：
在 博士研究生类中实现各个接口定义的抽象方法;
对年学费和年收入进行统计，用收入减去学费，求得纳税额；
国家最新纳税标准（系数），属于某一时期的特定固定值，与实例化对象没有关系，考虑如何用static  final修饰定义。
实例化研究生类时，可采用运行时通过main方法的参数args一次性赋值，也可采用Scanner类实现运行时交互式输入。
根据输入情况，要在程序中做异常处理。
实验步骤：
先用interface来定义两个接口，分别为学生和老师。
分别设计两个类，与上述接口相接。
开始设计系统主体，用输出函数把姓名，性别，年龄，月收入，学费写出来。然后输入文字引导程序运行，使用while语句作为约束语句。
利用for语句来循环变量
核心语句：
package guanLiXiTong;

class zhangSan implements xueShengJieKou,jiaoShiJieKou{
    
    public void jiaoNaXueFei(int xf) {
        System.out.print(xf);
    }
    
    public void faFangXinShui(int xs){
        System.out.print(xs);
    }
}
package guanLiXiTong;

class lisi implements xueShengJieKou,jiaoShiJieKou{
    
    public void jiaoNaXueFei(int xf) {
        System.out.print(xf);
    }
    
    public void faFangXinShui(int xs){
        System.out.print(xs);
    }
}
实验结果：
欢迎进入博士研究生管理系统
目前博士研究生有:
张三，男，28岁，所交学费（年）:无，所得薪水（年）:无，年应缴纳金额:无
李四，女，27岁，所交学费（年）:无，所得薪水（年）:无，年应缴纳金额:无
请输入张三所交学费（年）:2000
请输入李四所交学费（年）:1000
请输入张三所得薪水（年）:40000
请输入李四所得薪水（年）:58263
张三，男，28岁，所交学费（年）:2000，所得薪水（年）:40000，年应缴纳金额:3590
李四，女，27岁，所交学费（年）:1000，所得薪水（年）:58263，年应缴纳金额:5516

进程已结束,退出代码0
实验感想：
通过参考同学的代码，可以达到理解的程度。初步掌握了Java中接口的定义，接口的定义形式以及接口的实现方法，对于scanner输出函数和for循环函数加深了了解程度。一些细节的东西还需要自己去学习，毕竟是通过参考别人代码。自己没有独自完成的能力。

