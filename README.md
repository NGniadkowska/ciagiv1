# ciagiv1
// ciagi.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include "iostream"
#include "cstdlib"

using namespace std;
int main()
{	
	int nk;
	long long suma = 0;
	cout << "podaj liczbe" << endl;
	cin >> nk;
		for (int i = 1; i <= nk; i++)
			suma += i;
	
cout << suma << endl;
	system("PAUSE");
    return 0;
}
