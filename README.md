#include<stdio.h>
#include<conio.h>
void main()
{
int y;
scanf("%d",&y);
if(y%4==0)
{
if(y%100==0)
{
if(y%400==0)
{
printf("leap year");
}
else
{ printf("not a leap year");
}
}
else
{
printf("leap year");
}}
else
{
printf("not a leap year");
}
}
getch();
}
