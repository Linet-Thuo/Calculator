# Calculator
C++

#include <iostream>

using namespace std;

int main()
 {
	double num, den, result;
	char op;
	do {
		cout << "\nCalculator - Enter Number: ";
		cin >> num;
		cout << "Enter Operator +,-, *, /:";
		cin >> op;
		cout << "Enter Second Number: ";
		cin >> den;
		if (op=='+') result=num+den;
		if (op=='-') result=num-den;
		if (op=='*') result=num*den;
		if (op=='/') result=num/den;
		cout << result;
}
	while (op!='e');
	return 0;
}
