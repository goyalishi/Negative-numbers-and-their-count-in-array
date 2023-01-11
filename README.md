// Negative-numbers-and-their-count-in-array
#include <stdio.h>

int main()
{
int i,n,count=0;
scanf("%d",&n);
int arr[n];
   
   printf("Enter the values:");
   for(i=0;i<n;i++)
   {
       scanf("%d",&arr[i]);
       if(arr[i]<0)
       count++;}
       printf("negative elements are:\n");
       for(i=0;i<n;i++)
       { if(arr[i]<0)
       printf("%d\n",arr[i]);}
       printf("count is:%d",count);
       
    return 0;
}
