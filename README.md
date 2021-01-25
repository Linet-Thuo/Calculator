# Calculator
C++
![Calculator 1](https://user-images.githubusercontent.com/60045349/105732466-84c5ca80-5f41-11eb-83ec-1327da53cfd6.png)
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
