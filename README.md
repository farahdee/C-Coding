## C++ Coding

Example 1: Finding CGPA

```cpp
#include <iostream>
#include <string>
using namespace std;

int main ()
{
    string name;
    int age;
    double cgpa;

    cout << "Name: ";
    cin >> name;

    cout << "Age: ";
    cin >> age;

    cout << "CGPA: ";
    cin >> cgpa;

    cout << "Student Information" << endl << "----------" << endl;
    cout << "Name: " << name << endl;
    cout << "Age: " << age << endl;
    cout << "CGPA: " << cgpa << endl;

/Finding largest number between three integers
#include <iostream>
#include <string>
using namespace std;

int main ()
{
    int largest = 0;
    int num1, num2, num3;
    cout << "Enter three number (press enter to input another number): " ;
    cin >> num1 >> num2 >> num3;

    if (num1 > num2 && num1 > num3)
        largest = num1;
    else if (num2 > num1 && num2 > num3)
        largest = num2;
    else
        largest = num3;

    cout << "Largest number: " << largest;

    return 0;
}

/Finding final price
#include <iostream>
#include <string>
using namespace std;

int main ()
{
    double purchase, discount, finalPrice;

    cout << "Enter your purchase amount: ";
    cin >> purchase;

    if (purchase >= 100)
    {
        discount = 0.90;
        finalPrice = purchase * discount;
    }

    else if (purchase >= 50 && purchase <= 99)
    {
        discount = 0.95;
        finalPrice = purchase * discount;
    }

    else
    {
        finalPrice = purchase;
    }

    cout << "Your final price is: " << finalPrice;


    return 0;
}

    return 0;
}
