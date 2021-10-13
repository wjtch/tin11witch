//# tin11witch
//Starting online-classes with C++, nothing much.

//tinh cong thuc dien tich hinh tron
#include <iostream>
#include <math.h>
using namespace std;
int main()
{
	const float pi = 3.14;
	float R;
	cout << "Nhap ban kinh duong tron: ";
	cin>>R;
	
	float S = 0.5 * pi * pow(R,2);
	cout<<"Dien tich hinh tron la: "<< S;
	return 0;
}
