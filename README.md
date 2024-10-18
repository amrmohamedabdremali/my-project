# my-project
 el zero school

 
/*
variables scope
  global variable
  local variable
  */

#include <iostream>

using namespace std;

int a = 100; // globel varible
int b = 200; // globel varible

int second()

{
    cout << a << "coming from second function\n";
    cout << b << "coming from second function\n";

    return 0 ;
}

int main()
{
    cout << a << "coming from main function\n";
    cout << b << "coming from main function\n";

    second();
    return 0;
}
