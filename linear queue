#include<stdio.h>
void insert(int item,int *r,int q[]);
int delete(int *r,int q[],int *f);
void display(int q[],int f,int r);
void insert(int item,int *r,int q[])
{
if(*r==99)
{
printf("queue is full\n");
return;
}
*r=*r+1;
q[*r]=item;
}
int delete(int *r,int q[],int *f)
{
int item;
if(*f>*r)
{
printf("queue is empty\n");
return -9999;
}
item=q[*f];
*f=*f+1;
return item;
}
void display(int q[],int f,int r)
{
int i;
if(f>r)
{
printf("queue is empty\n");
return;
}
printf("contents of queue are\n");
for(i=f;i<=r;i++)
{
printf("%d",q[i]);
}
}
int main()
{
int q[100],f=0,r=-1,b,ele,i=0,e;
do
{
printf(" Press 1: insert\n Press 2: delete\n Press 3: Display\n Press 4:Exit\n");
scanf("%d",&b);
switch(b)
{ case 1: printf("Enter the element you want to insert :\n");
          scanf("%d",&ele);
          insert(ele,&r,q);
          break;

  case 2: e=delete(&r,q,&f);
          if(e!=9999)
          {
            printf("The deleted element is %d\n",e);
          }
          break;

  case 3: display(q,f,r);
          break;

  case 4: break;
  
  default: printf("you have entered a wrong key\n");
           break;
};
}while(b!=4);

return 0;
}
