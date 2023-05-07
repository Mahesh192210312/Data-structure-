#include<stdio.h>
#include<conio.h>
int main ()
{
	int arr[50],position,c,n,value;
	printf("emter the number of elements in the array\n");
	scanf("%d",&n);
	printf("enter %d elements\n",n);
	for(c=0;c<n;c++)
	scanf("%d",&arr[c]);
	printf("please enter the location where you want to insert an new element");
	scanf("%d",&position);
	printf("please enter the value\n");
	scanf("%d",&value);
	for(c=n-1;c>=position-1;c--)
	arr[c+1]=arr[c];
	arr[position-1]=value;
	printf("%d\n",arr[c]);
	getch();
	return 0;
}
