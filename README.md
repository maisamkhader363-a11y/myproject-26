#include<iostream>
#include<cstdlib>
#include<ctime>
using namespace std;
int main()
{
	int num1 = (rand() % 50) + 20;
	int num2 = (rand() % 50) + 20;
	int num3 = (rand() % 50) + 20;
	int num4 = (rand() % 50) + 20;
	int num5 = (rand() % 50) + 20;
	//print the numbers in the order they were generated
	cout << "Print the numbers in the order they were generated" << endl;
	cout << "Random number 1:" << num1 << endl;
	cout << "Random number 2:" << num2 << endl;
	cout << "Random number 3:" << num3 << endl;
	cout << "Random number 4:" << num4 << endl;
	cout << "Random number 5:" << num5 << endl;
	//print whether its even or odd
	if (num1 % 2 == 0)


		cout << num1 << ": even number" << endl;
	else
		cout << num1 << ":odd number" << endl;

	if (num2 % 2 == 0)
		cout << num2 << ":even number" << endl;
	else
		cout << num2 << ":odd number" << endl;

	if (num3 % 2 == 0)
		cout << num3 << ":even number" << endl;
	else
		cout << num3 << ":odd number" << endl;
	if (num4 % 2 == 0)
		cout << num4 << ":even number" << endl;
	else
		cout << num4 << ":odd number" << endl;
	if (num5 % 2 == 0)
		cout << num5 << ":even number" << endl;
	else
		cout << num5 << ":odd number" << endl;
	int sum = 0;
	int count1 = 0;
	int count2 = 0;
	if (num1 % 2 == 0) count1++;             if (num1 % 2 != 0) count2++;
	if (num2 % 2 == 0)count1++;              if (num2 % 2 != 0) count2++;
	if (num3 % 2 == 0) count1++;             if (num3 % 2 != 0) count2++;
	if (num4 % 2 == 0) count1++;             if (num4 % 2 != 0) count2++;
	if (num5 % 2 == 0) count1++;             if (num5 % 2 != 0) count2++;
	cout << "The count of even numbers=" << count1 << endl;
	cout << "The count of odd numbers=" << count2 << endl;
	cout << "The sum of generated numbers=" << num1 + num2 + num3 + num4 + num5 << endl;
}
