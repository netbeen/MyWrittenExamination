# 2015年腾讯实习生在线笔试题
## 不定项选择题
1. 关于图的存储结构，下列说法不正确的是（）。  
A. 图是有顺序映像的存储结构  
B. 图的存储结构可以用数组来表示  
C. 在实际应用中适宜采用多重链表来表示图的存储结构  
D. 对于无向图来说，可以用邻接多重链表来存储  

2. 下面哪些按钮标签能够让用户点击后直接提交表单？（）  
A. \<input type="submit" />  
B. \<input type="image" />  
C. \<input type="button" />  
D. \<input />  

3. 请问下面代码的输出是什么？（）  
```
class A{
public:
	~A(){
		printf("A");
	}
};
class B{
public:
	~B(){
		print("B");	
	}
}
class C : public A{
public:
	~C(){
		printf("C");
	}
private:
	B _b;
};
int main(){
	C c;
	return 0;
}
```


## 简答题
