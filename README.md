#include <iostream>
using namespace std;
void main()
{
	int a[10][10];
	for (int i = 0; i < 10; i++)
	{
		for (int j = 0; j < 10; j++)
		{
			cin >> a[i][j];
		}
	}
	int x, y, n,m;
	cout << "enter x,y:";
	cin >>x >> y;
	for (int j = 0; j < 10; j++)
	{
		for (int i = 0; i < 10; i++)
		{
			if (a[i][j] == x)
			{
				n = x;
			}
			else if (a[i][j] == y)
			{
				m = y;
			}
		}

	}
	cout << n << endl;
	cout << m;
}

