//14oktabr zadn1
// ConsoleApplication31.cpp: определяет точку входа для консольного приложения.
//

#include "stdafx.h"
#include <iostream>
#include <string>
#include <math.h>
using namespace std;

int _tmain(int argc, _TCHAR* argv[])
{
	int m;
	int n;
	int s = 0;
	cout << "m=";
		cin >> m;
		cout << "n=";
	cin >> n;
	for (int i = 1; i <=m ; i++){
		s = pow(i,n) + s;
		cout << s << endl;
	}
	cout << endl;
	cout << s << endl;
	system("pause");
	return 0;
}
