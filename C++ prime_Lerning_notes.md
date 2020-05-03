1.C++中&引用的用法
  引用就是给一个变量起一个别的名字。
例：
#include<iostream>
using namespace std;
void main() 
{
	int i = 100;              //定义整型i
	int& k=i;                   //int&为定义引用类型，
	k = 5;
	cout << k<<"\t"<<i;
}
