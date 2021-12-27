# pointer-and-inheritance-Virtual-funcation
////pointer and inheritance
//#include<iostream>
//using namespace std;
//class A{
//	public:
//		void show(){
//			cout<<"Parants class a"<<endl;
//		}
//};
//class B:public A{
//		public:
//		void show(){
//			cout<<"child class b"<<endl;
//		}
//	
//};
//class C:public A{
//		public:
//		void show(){
//			cout<<"child class C"<<endl;
//		}
//	
//};
//int main(){
//	A ob;
//	A *ptr;
//	B ob1;
//	C ob2;
//	ptr=&ob;
//	ptr->show();
//	ptr=&ob1;
//	ptr->show();
//	ptr=&ob2;
//	ptr->show();
//	return 0;
//}
//pointer and inheritance                 Virtual funcation
#include<iostream>
using namespace std;
class A{
	public:
		void virtual show(){
			cout<<"Parants class a"<<endl;
		}
};
class B:public A{
		public:
		void show(){
			cout<<"child class b"<<endl;
		}
	
};
class C:public A{
		public:
		void show(){
			cout<<"child class C"<<endl;
		}
	
};
int main(){
	A ob;
	A *ptr;
	B ob1;
	C ob2;
	ptr=&ob;
	ptr->show();
	ptr=&ob1;
	ptr->show();
	ptr=&ob2;
	ptr->show();
	return 0;
}
