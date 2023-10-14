# Rec-plus-star
#include<stdio.h>
void main()
{
int n;
printf("Enter any number ");
scanf("%d",&n);

for(int I=1;I<=n;I++)
{
for (int j=1;j<=n;j++)
{
if(I==1 || j==1 || I==n ||j==n ||I ==j || I+j==n+1 || (n/2)+1==I || (n/2)+1==j)
printf(" *");
else
printf("  ");
}
printf("\n");
}

}
