# Show-The-Minimum-Amount-of-Integers

# include <iostream>
#include <conio.h>
using namespace std;
int main()

{
	int a,b,c ;
	cout<<"Enter Three Integers :  "<<endl;
	cout<<"a : ";
	cin>>a;
	cout<<"Enter b: ";
	cin>>b;
	cout<<"Enter c: ";
	cin>>c;
	
	int minimum = a;
	
	if (b<minimum) minimum=b ;
	if (c<minimum) minimum=c ;
	
	cout<<"Their Minimum Is: "<<minimum<<endl;
	
	getch();
	
	
	
}
