#include<stdio.h>
int main()
{
int c,first,last,middle,n,search,a[20];
printf("enter the size of a array");
scanf("%d",&n);
printf("enter the %d elements\n",n);
for (c=0;c<n;c++)
scanf("%d",&a[c]);
printf("enter a number to search\n",n);
scanf("%d",&search);
first=0;
last=n-1;
middle=(first+last)/2;
while (first<=last)
{
if (a[middle]<search)
first=middle+1;
else if(a[middle]==search)
{
printf("%d is found in location %d\n",search,middle+1);
break;
}
else
last=middle-1;
middle=(first+last)/2;
}
if (first>last)
printf("%d is not found in array\n",search);
return 0;
}
