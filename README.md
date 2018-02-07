#include <stdio.h>
int main()
{
	int n;
	long long  sum=0,temp;
	scanf("%d",&n);
	temp=n;
	printf("%I64d\n",(1+temp)*temp/2);
	return 0;
}
