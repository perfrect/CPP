# CPP
#define  _CRT_SECURE_NO_WARNINGS 1
#include  <stdio.h>
int Add(int x, int y)
{
	int z = x + y;
	return z;
}
int main()
{
	int a=0,b=0,sum=0;
	printf("a=",a);
	scanf("%d", &a);
	printf("b=",b);
	scanf("%d", &b);
	sum = Add(a, b);
	printf("sum=%d\n",sum);
	return 0;
}
