# CSC242Pro
My first repos

#include <iostream>
#include <string>

using std::cout;
using std::endl;
using std::cin;

void squareOfAsterisks(unsigned n)
{
	for (size_t row = 0; row < n; row++)
	{
		for (size_t col = 0; col < n; col++)
		{
			cout << "*";
		}
		cout << endl;
	}
}

int main()
{
	unsigned n = 0;
	cout << "Enter num ";
	cin >> n;

	squareOfAsterisks(n);

	return 0;
}
