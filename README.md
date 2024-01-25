#include <iostream>

#define _CRT_SECURE_NO_WARNINGS

int main(void)
{
	double num = 0;
	double i = 1;
	double result = 1;

	std::cout << "What integer would you like to find the factorial for";
	std::cin >> num;

	for (; i <= num; i++)
	{
		result = result * i;
	}
	//result = result * num;

	std::cout << "factorial: " << result << std::endl;


	return 0;
}
