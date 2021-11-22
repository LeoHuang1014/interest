# interest
counting the interest of your money

#include <iostream>
#define rate 0.015
using namespace std;

int main()
{ 
 int myAccount;
 cout<<"input amount of your account \0";
 
 cin>>myAccount;
 cout<<"The interest of your account is \0"<<myAccount*rate<<endl;
 
 return 0;
} 
