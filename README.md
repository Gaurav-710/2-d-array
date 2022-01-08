# 2-d-array
//2. Write a C program to subtract two matrices in third matrix (Using Static memory Allocation).


#include<stdio.h>
void main()
{int R,C;
printf("enter no rows");
scanf("%d",&R);
printf("enter no column");
scanf("%d",&C);
int arr1[10][10];
int arr2[10][10];
int arr3[10][10];
int i;
int j;
printf("enter fisrt matrix");
for(i=0;i<R;i++)
{
     for(j=0;j<C;j++)
       {

        scanf("%d",&arr1[i][j]);     

      }


} 
for(i=0;i<R;i++)
{ 
     for(j=0;j<C;j++)
       {

        printf("%d  ",arr1[i][j]);     

      }
    printf("\n");

}
 
printf("enter second matrix\n");   
for(i=0;i<R;i++)
{
     for(j=0;j<C;j++)
       {

        scanf("%d",&arr2[i][j]);     

      }


}
for(i=0;i<R;i++)
{ 
     for(j=0;j<C;j++)
       {

        printf("%d  ",arr2[i][j]);     

      }
    printf("\n");

}
printf("substraction  of two matrix\n");    
for(i=0;i<R;i++)
{ 
     for(j=0;j<C;j++)
       {

        printf("%d  ",arr3[i][j]=arr1[i][j]-arr2[i][j]);     

      }
    printf("\n");

}


}
