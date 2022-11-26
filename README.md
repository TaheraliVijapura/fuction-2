# fuction-2

#include <stdio.h>
	void add(int a,int b)
{
	printf("\n add =%d",a+b);
}

	void mul(int a,int b)
	{
		printf("\n mul = %d",a*b);
	}
	
		void div(int a,int b)
	{
		printf("\n div = %d",a/b);
	}
	
	void cube(int a)
	{
		printf("\ncube = %d",a*a*a);
	}
main()
{
	int a,b;
	printf("\n enter the values:");
	scanf("%d%d",&a,&b);
	
	add(a,b);
	mul(a,b);
	cube(a);
	div(a,b);
}
