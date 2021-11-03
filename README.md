#include <iostream>
using namespace std;

    int stack[100], size = 100,pos = -1;
    void push(int val){
        pos++;
        stack [pos]=val;
        }
    int main()
    {
        cout<<"size of array " <<size<<endl;
       
    push(12);
    push(1);
    push(2);
    push(32);
    push(112);
    ++pos;
        cout<<pos<<endl;
    return 0;
    }
