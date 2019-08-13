#include <stdio.h>
#include <stdlib.h>
#include<conio.h>
struct student
{
int marks[50],grade[60],credits[70];
float sgpa;
}s;
int main() 
{
int i,n,sum = 0,c=0;
float sgpa;
clrscr();
printf("Enter no of subjects: \n");
scanf("%d",&n);
printf("enter the marks and credits:\n");
for(i = 0; i<n; i++)
{
scanf("%d",&s.marks[i]);
scanf("%d",&s.credits[i]);
printf("\n");
}
for(i = 0; i<n; i++)
{
if(s.marks[i]>=90)
{
s.grade[i] = 10;
}
else
if(s.marks[i]>=75 && s.marks[i]<90)
{
s.grade[i] = 9;
}
else
if(s.marks[i]>=60 && s.marks[i]<75)
{
s.grade[i] = 8;
}
else
if(s.marks[i]>=50 && s.marks[i]<60)
{
s.grade[i] = 7;
}
else
if(s.marks[i]>=45 && s.marks[i]<50)
{
s.grade[i] = 5;
}
else
if(s.marks[i]>= 40 && s.marks[i]<45)
{
s.grade[i] = 4;
}
else
if(s.marks[i]>=0 && s.marks[i]<45)
{
s.grade[i] = 0;
}
else
{
printf("Invalid");
getch();
exit(1);
}
}
for(i = 0; i<n; i++)
{
sum = sum + (s.grade[i]*s.credits[i]);
}
for(i=0;i<n;i++)
{
c=c+s.credits[i];
}
sgpa = sum/c;
printf("sgpa is %f",sgpa);
getch();
return 0;
}
