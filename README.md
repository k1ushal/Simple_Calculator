# Simple_Calculator
This is a Simple calculator program written in C language. Its just a timepass practice.



#include <stdio.h>
<pre>
int main()
{
	printf("Simple Calculator \n You can only do mathematical operations with 2 numbers only,\n such as 6-2 (Don't enter spaces) \n (Addition, Subtraction, Multiply and Divide are supported) \nCreator : https://github.com/k1ushal/\n \n \n");
	float a, b;
	char o;
	scanf("%f", &a);
	scanf("%c", &o);
	scanf("%f", &b);
	if (o == '+')
	{
		printf("= %f", a + b);
	}
	else if (o == '-')
	{
		printf("= %f", a - b);
	}
	else if (o == '*')
	{
		printf("= %f", a * b);
	}
	else if (o == '/')
	{
		printf("= %f", a / b);
	}
	else
	{
		printf("invalid Operation, Please Start Again ( + , - , * , / )");
	}
	printf("\n\n\n\n\n\n");
	printf("Thanks for using this program.\n Upgrades on this program will be updated soon\n- Kushal");

	return 0;
}</pre>
