# 2015年腾讯实习生在线笔试题
## 不定项选择题
1\. 关于图的存储结构，下列说法不正确的是（）。  
A. 图是有顺序映像的存储结构  
B. 图的存储结构可以用数组来表示  
C. 在实际应用中适宜采用多重链表来表示图的存储结构  
D. 对于无向图来说，可以用邻接多重链表来存储  

2\. 下面哪些按钮标签能够让用户点击后直接提交表单？（）  
A. \<input type="submit" />  
B. \<input type="image" />  
C. \<input type="button" />  
D. \<input />  

3\. 请问下面代码的输出是什么？（）  
```C++
class A{
public:
	~A(){ printf("A"); }
};
class B{
public:
	~B(){ print("B"); }
}
class C : public A{
public:
	~C(){ printf("C"); }
private:
	B _b;
};
int main(){
	C c;
	return 0;
}
```

4\. 关于动态库和静态库，以下说法正确的是（）。  
A. 静态链接库在编译以后包含在可执行文件中，不会以单独文件的形式存在  
B. 动态链接库是以单独文件的形式存在，被程序外部调用  
C. 动态链接库的好处就是可以多个进程访问一个动态链接库  
D. 动态链接库共享一块内存，静态则包含在程序中，不能被外部调用

5\. 关于malloc和new，以下说法正确的是（）。  
A. new是C++的关键字  
B. malloc在分配内存时必须按给出的字节分配  
C. new可以按照对象的大小自动分配，并且能调用构造函数  
D. new分配内存时，还会在实际内存快的前后加上附加信息，所以new使用的内存大小比malloc多  

6\. 若数据元素序列10，11，12，5，6，7，20，2，3是采用下列排序方法之一得到的第二趟排序后的结果，则该排序算法只能是（）。  
A. 冒泡排序  
B. 选择排序  
C. 二路归并排序  
D. 插入排序  

7\. 程序输出的结果是（）。  
```C++
typedef struct_A{
	char a;
	int b;
	float c;
	double d;
	int *pa;
	char *pc;
	short e;
}A;
#pragma pack(pop)
int main(a=int argc, char *argv[]){
	printf("size=%d\n",sizeof(A));
	return 0;
}
```
8\. 用二分法查找一个长度为20的，排好序的线性表，查找不成功时，最多需要比较多少次（）
A. 5  
B. 7  
C. 4  
D. 6  

9\. 应用层DNS协议主要用于实现（）网络服务功能。
A. IP地址到网络设备名字的映射  
B. IP地址到网络硬件地址的映射  
C. 网络设备名字到IP地址的映射  
D. 网络硬件地址到IP地址的映射

10\. 在MVC模式中，进行业务流程/状态处理以及业务规则制定的是（）。
A. Model  
B. Manager  
C. View  
D. Controller  

11\. 下面程序的输出结果是（）。
```C++
class Base{
public:
	Base(int i){cout << i;}
	~Base(){}
};
class Base1 : virtual public Base{
public:
	Base1(int i, int j = 0) : Base(j){cout << i;}
	~Base1(){}
};
class Base2 : virtual public Base{
public:
	Base2(int i, int j = 0) : Base(j){cout << i;}
	~Base2(){}
}
class Derived : public Base2, public Base1{
public:
	Derived(int a, int b, int c, int d) : mem1(a), mem2(b), Base1(c), Base2(d), Base(a){cout << b;}
private:
	Base2 mem2;
	Base1 mem1;
};
void main(){
	Derived objD(1,2,3,4);
}
```

12\. 关于递归，说法正确的是（）。
A. 递归函数是一个直接调用自己或通过一系列的调用语句间接地调用自己的函数  
B. 对二叉树，广义表适宜用递归来进行描述操作  
C. 递归函数重复多次的自我调用不会对栈造成任何影响  
D. 递归函数面对的大部分问题都可以使用迭代函数来解决  

13\. 在定义int a[3][4][2];以后，第10个元素是（）。
A. a[2][1][2]  
B. a[1][0][1]  
C. a[2][0][1]  
D. a[2][2][1]  

14\. 对于移动平均算法，是计算某变量之前那个数值的算术平均，用哪些数据结果记录历史变量，性能可以达到最优？（）  
A. 数组  
B. 双向链表  
C. 单项链表  
D. 二叉树

15\. 以下这段代码的运行结果是（）。
```C++
char *b = "hello";
char *b = "tencent";
printf("%s %s %s", a,b);
```
A. 编译错误
B. 输出hello tencent  
C. 运行结果不可预知  
D. 无法运行  

## 简答题
