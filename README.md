# Cospro_5
#include <stdio.h>

int main(void)
{
	printf("test\"I am a student\"test");
	return 0;
}
/////////////////////////////
#include <stdio.h>

int main(void)
{
	int myAge = 20;
	printf("제 나이는 10진수로는 %d살, 16진수로는 %x살입니다.\n", myAge, myAge);
	return 0;
}
///////////////////////////
#include <stdio.h>

int main(void)
{
	printf("%f\n", 0.1234);
	printf("%e\n", 0.1234);  // e표기법 기반의 출력
	printf("%f\n", 0.12345678);
	printf("%e\n", 0.12345678);
	return 0;
}
/////////////////////////
#include <stdio.h>

int main(void)
{
	double d1 = 1.23e-3;  //0.00123
	double d2 = 1.23e-4;  //0.000123
	double d3 = 1.23e-5;  //0.0000123
	double d4 = 1.23e-6;  //0.00000123

	printf("%e\n", d1);
	printf("%e\n", d2);
	printf("%e\n", d3);
	printf("%e\n", d4);

	return 0;
}
///////////////////
#include <stdio.h>

int main(void)
{
	float num1;
	double num2;
	long double num3;
	printf("실수 입력1(e 표기법으로) : ");
	scnaf("%f", &num1);
	printf("입력된 실수 %f \n", num2);
	printf("실수 입력2(e 표기법으로) : ");
	scnaf("%lf", &nu32);
	printf("입력된 실수 %Lf \n", num3);
	return 0;
}
