//find the no is prime or not and find multipliers of given no.

#include <stdio.h>

int main() {
	int i=1,n,count=0;
	printf("enter the value of n");
	scanf("%i",&n);
	while(i<=n){
		if(n%i==0)
		{
			printf("\n%i",i);
			count=count+1;
	i=i+1;
		}
		else
		{
			i=i+1;
		}
		}
		{
		if(count>2)
		{
			printf("\n%i is not a prime no.",n);
		}
		else
		{
			printf("\n%i is a prime no.",n);
		}
		}
	return 0;
}
