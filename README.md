# Recursive-function
#include <iostream>
using namespace std;

//recursive function

int sum(int n)
{
	if (n == 0)
	{
		return 0;
	}
	else
	{
		return n + sum(n - 1);
	}
}

int main()
{
	int n;
	cout << "Enter a value for n ";
	cin >> n;

	int answer = sum(n);

	cout << answer;

	return 0;

}
