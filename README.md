#include<iostream>
using namespace std;
class Calculator{
    float n1,n2;
    float addition;
    float subtraction;
    float multiplication;
    float division;
public:
     Calculator(){

    cout<<"enter first number"<<endl;
    cin>>n1;
    cout<<"enter second number"<<endl;
    cin>>n2;
    }
    void add(){
        addition=n1+n2;
        cout<<"addition of the two numbers is  "<<addition<<endl;
    }
    void sub(){
        addition=n1-n2;
        cout<<"subtraction of the two numbers is  "<<subtraction<<endl;
    }
    void mul(){
        multiplication=n1*n2;
        cout<<"multiplicaiton of the two numbers is  "<<multiplication<<endl;
    }
    void div(){
        division=n1/n2;
        cout<<"division of the two numbers is   "<<division<<endl;
    }
};
int main(){
Calculator C1;
int choice;
cout<<"enter 1:add 2:sub 3:mull 4:div"<<endl;
cin>>choice;
switch(choice){
case 1:
     C1.add();
    break;
case 2:
    C1.sub();
    break;
case 3:
    C1.mul();
    break;
case 4:
    C1.div();
    break;
default:
    break;
    }
return 0;
}
# simple-calculator
