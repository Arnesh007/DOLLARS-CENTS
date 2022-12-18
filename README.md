# DOLLARS-CENTS
Write a C++ program to add two dollars and cents:

Sample Input:
30
10
140
99

Sample Output:
171
9

ANSWER:
#include<iostream>
using namespace std;
int main()
{
     int a,b,c,d,e,f,g,h;
     cin>>a>>b>>c>>d;
     e=a+c;
     f=b+d;
     if(f>99)
     {
         h=f/100;
         g=f%100;
         
     }
     else
     {
         g=b+d;
     }
    
         cout<<e+h<<endl<<g;
        return 0;
}
