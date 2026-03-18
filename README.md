WEEK-1 
1. WRITE A C++ PROGRAM TO DISPLAY NAME, ROLLNO, BRANCH, SECTION , BY USING COUT
program:
#include <iostream>
using namespace std;

int main() 
{
    cout << "Name    : Siri Chandana" << endl;
    cout << "Roll No : 23A91A0501" << endl;
    cout << "Branch  : CSE" << endl;
    cout << "Section : A" << endl;

    return 0;
}
2. WRITE A C++ program to identify biggest value among given three value
program:
#include <iostream>
using namespace std;

int main() {
    int a, b, c;

    cout << "Enter three numbers: ";
    cin >> a >> b >> c;

    if (a >= b && a >= c)
        cout << "Biggest number is: " << a;
    else if (b >= a && b >= c)
        cout << "Biggest number is: " << b;
    else
        cout << "Biggest number is: " << c;

    return 0;
}
3.Write a C++ program to indentify whether the given number is leap year or not
Program:
#include<iostream>
using namespace std;
int main()
{
int n;
cout<<"enter a year";
cin>>n;
if(n%4==0&& n%100==0//n%400==0)
cout<<"leap year";
else
cout<<"not a leap year";
return 0;
}

4.Write a c++ program to calculate Factorial of a given number.
PROGRAM
#include <iostream>
using namespace std;
int main(){
int n,fact=1;
cout << "enter in value";
Cin>>n;n=3
if (n==0)
Cout<<fact;
else
for (int i=1; i<=n; i++)
fact = fact*1;
cout << "factorial value is "<< fact;
return 0;
OUTPUT
Enter n value 5
Factorial value-120

5.Write a c++ program to decide whether the given number is prime or not.
PROGRAM:
#include <iostream> 
using namespace std; 
int main()
{
intn, count=0; 
cout <<"enter n'value";
Cin>>n; 
for (int i=1; i<=n; i++) { 
if (n%i==0) count = count+1; 
if (count=-2) count <<n<<< " is prime number;
else
count<< n<< "is not prime number; 
return 0;
}
OUTPUT
Enter n value - 5
5 is prime number
