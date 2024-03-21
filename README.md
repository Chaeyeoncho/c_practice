#include <stdio.h>
int main(void)
{
	float amount, tax_added;
	printf("Enter an amount : ");
	    scanf_s("%f",&amount);
		
		tax_added = amount * 1.05;
			printf("With tax added :  %.2f\n",tax_added);
		
	return 0;
}
