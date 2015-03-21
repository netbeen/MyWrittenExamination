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
\8. 

## 简答题
