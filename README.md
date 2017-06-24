#include<stdio.h>
void main()
{
	float a,s=1;
	int i;
	for(i=2;i<=100;i+=2)
	{
		a=(float)(i*i)/((i-1)*(i+1));
		s*=a;
	}
	printf("s=%f\n",2*s);
}
