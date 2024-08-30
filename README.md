#include <iostream>
using namespace std;

int main() {

	//pengenalan data
	float a, b, hasil;
	char aritmatika;

	cout << "masukkan angka pertama: ";
	cin >> a;
	cout << "masuukkan +,-,/,* :";
	cin >> aritmatika;
	cout << "masukkan angka kedua: ";
	cin >> b;

	//hasil perhitungan
	cout << a << aritmatika << b;

	//program
	switch (aritmatika) {
		case '+':
			hasil = a + b;
			cout << " = " << hasil << endl;
			break;
		case '-':
			hasil = a - b;
			cout << " = " << hasil << endl;
			break;

		case '/':
			hasil = a / b;
			cout << " = " << hasil << endl;
			break;

		case '*':
			hasil = a * b;
			cout << " = " << hasil << endl;
			break;

		default:
			cout << "Operasi gagal" << endl;

	}	

	cout << "program selesai" << endl;



	cin.get();
	return 0;
}
