# Godslove
Tutorial
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
# include <iostream>
# include <string>
using namespace std;
int main()
{
  int a,b,c;
  cout<< "Enter two nos :"<<endl;
  cout<< "Enter first no. : ";
  cin>>a;
  cout<< "Enter sec. no. : ";
  cin>>b;
  c=a*b;
  while(a!=b)
    {
      if(a>b)
        a=a-b;
      else
        b=b-a;
    }
  cout<< "HCF = " << a<<endl;
  cout<< "LCM = " << c/a<<endl;
  return 0;
}
 
/*
OUTPUT:
Enter two nos :
Enter first no. : 5
Enter sec. no. : 9
HCF = 1
LCM = 45
*/
back that a## up like it's 1999
new stuff