techapp
=======
#include<iostream.h>
#include<stdio.h>

void main()
clrscr()
{
int i,fact;
int factorial (int n);
cout<< "enter the factorial no"<< endl;
cin>>4;
fact = factorial(4);
 cout << "factorial of 4 = "<< fact<< endl;
 }
 int factorial (int n)
  if (n==0)
  {
  return 1;
  }
  else
  {
  return n*(factorial (n-1));
  }
 
 
