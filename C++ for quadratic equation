#include<iostream>
#include<cmath>
using namespace std;

//main driver application
int main(){
	float a;
	float b;
	float c;
	float x1;
	float x2;
	float discriminant;
	//the discriminant in a quadratic equation is sqrt(b squared-4ac)
	float realPart;
	float imaginaryPart;
// enter the values of a,b and c

	cout << "enter the values of a b and c" << endl;
	cin >> a >> b >> c;
	discriminant = (b*b)-(4*a*c);

	//conditional statements based on mathematical reasoning
	if(discriminant > 0){
		x1 = (-b + sqrt(discriminant))/2*a;
		x2 = (-b - sqrt(discriminant))/2*a;
		cout << "The values of x1 and x2 is :"<< endl;
		cout <<"x1="<< x1 <<"x2=" << x2 << endl;
	} else if(discriminant == 0) {
		x1 = (-b + sqrt(discriminant))/2*a;
		x1 == x2;
		cout << "The values of x1 and x2 are the same:" << endl;
		cout <<"x1 $ x2:"<< x1 << endl;
	} else{
		realPart = -b/(2*a);
		imaginaryPart = sqrt(-discriminant)/(2*a);
        cout << " The roots are complex $ imaginary"<< endl;
        cout << "x1=" << realPart << "+" << imaginaryPart << "i" << endl;
        cout << "x2=" << realPart << "-" << imaginaryPart << "i" <<endl;
	}
	return 0;
}
