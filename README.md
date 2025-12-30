# calculator
#include<iostream>
using namespace std;
int main()
{
        int a,b;
        char op;
        cout<<"enter first number:";
        cin>>a;
        cout<<"enter second number:";
        cin>>b;
        cout<<"enter operator:";
        cin>>op;
        switch(op){
                case('+'):
                        cout<<"result is"<<a+b;
                        break;
                                case('-'):
                        cout<<"result is"<<a-b;
                        break;
                             case('*'):
                        cout<<"result is"<<a*b;
                        break;
                           case('/'):
                        cout<<"result is"<<a/b;
                        break;

}
}