# 211-7211
//Задача1
#include <iostream>
using namespace std;
int a, b;
int main() {
	setlocale(LC_ALL, "Russian");
	cout << "a= ";
	cin >> a;
	cout << "b= ";
	cin >> b;
	cout << "S= " << a * b << endl;
	cout << "P= " << 2*(a + b);
}

//Задача2
#include <iostream>
using namespace std;
int d;
float P = 3.14;
int main() {
	setlocale(LC_ALL, "Russian");
	cout << "d= ";
	cin >> d;
	cout << "L= " << d * P;
}

//Задача3
#include <iostream>
using namespace std;
int a, b;
int main() {
	setlocale(LC_ALL, "Russian");
	cout << "a= ";
	cin >> a;
	cout << "b= ";
	cin >> b;
	cout << "Результат: " << (a + b) / 2;
}

//Задача4
#include <iostream>
using namespace std;
int a, b;
int main() {
	setlocale(LC_ALL, "Russian");
	cout << "a= ";
	cin >> a;
	cout << "b= ";
	cin >> b;
	cout << "Сумма = " << (a * a) + (b * b) << endl;
	cout << "Разность = " << (a * a) - (b * b) << endl;
	cout << "Произведение = " << (a * a) * (b * b) << endl;
	cout << "Частное = " << (a * a) / (b * b) << endl;
}

//Задача5
#include <iostream>
using namespace std;
int a, b;
int main() {
	setlocale(LC_ALL, "Russian");
	cout << "a= ";
	cin >> a;
	cout << "b= ";
	cin >> b;
	cout << "Сумма = " << abs(a) + abs(b) << endl;
	cout << "Разность = " << abs(a) - abs(b) << endl;
	cout << "Произведение = " << abs(a) * abs(b) << endl;
	cout << "Частное = " << (double)abs(a) / abs(b) << endl;
}
