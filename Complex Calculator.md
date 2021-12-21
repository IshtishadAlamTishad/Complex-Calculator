#include<bits/stdc++.h>
using namespace std;
int main ()
{
 long long int a,b;
 double result;
 char op;
 for(int i=0;i<100;i++) {
 cout << "Enter first number: " << endl;
 cin >> a;
 cout << "Enter second number: " << endl;
 cin >> b;
 cout << "Choose an Operator : (+,-,*,/,%) : " << endl;
 cin >> op;
 if(op=='+') {
 result = a+b;
} else if(op=='-') {
 result = a-b;
} else if(op=='*') {
 result = a*b;
} else if(op=='/') {
 result = a/b;
} else if(op=='%') {
 result = a%b;
}
 cout << "The answer is : " << result << endl;
 cout << endl;
}
 return 0;
}
