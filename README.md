# fungsi-luas-lingkaran

#include <iostream>
#include <cmath>
using namespace std;

double luaslingkaran(double r){
	double pi = M_PI;
	return pi*r*r;
}

int main(){
	double r;
	
	cout << "input angka";
	
	cin >>  r;
	
	cout <<"luas lingkaran: " << luaslingkaran (r);
	
	return 0;
}
