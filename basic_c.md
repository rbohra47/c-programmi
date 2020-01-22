	 # Area of Circle #
```c
#include<stdio.h>
#include<conio.h>
void main()
{
float a,area;
printf("enter the number");
scanf("%f",&a);
area=3.14*a*a;
printf("area of circle=%f",area);
}
  ```
# Ascii value of character #
```c
  #include<stdio.h>
#include<conio.h>
 void main()
 {
     char ch;
     printf("\n enter any character:");
     scanf("%c",&ch);
     printf("\n the ascii value of %c is:%d",ch,ch);
     return 0;
 }
```
#character in upper case then print in lower case#
```c
     #include<stdio.h>
#include<conio.h>
void main()
{

    char ch;
    printf("\n enter the character in upper case");
    scanf("%c",&ch);
    printf("\n the character is lower case %c",ch+32);
    return 0;
}
```
#last digit first digit#
```c
#include<stdio.h>
#include<conio.h>

  void main()
  {
      int num,a;
      printf("enter the value");
      scanf("%d",&num);
      a=num%10;
      while(num>10)
      {
          num=num/10;
      }
      printf("digit of ones place %d:",a);
            printf("\n digit of first digit place %d:",num);
      return 0;

  }
```
#swap two number#
```c
#include<stdio.h>
#include<conio.h>
void main()
{
    int num1,num2,temp;
    printf("enter the number num1");
    scanf("%d",&num1);
    printf("enter the number num2");
    scanf("%d",&num2);
    temp=num1;
    num1=num2;
    num2=temp;
    printf("the first number is %d",num1);
    printf("the second number is %d",num2);
    return 0;
}

```
#swap to number without temporary variable#
```c
#include<stdio.h>
#include<conio.h>
void main()
{
    int num1,num2;
    printf("enter the number num1");
    scanf("%d",&num1);
    printf("enter the number num2");
    scanf("%d",&num2);
    num1=num1+num2;
    num2=num1-num2;
    num1=num1-num2;
    printf("the first number is %d",num1);
    printf("the second number is %d",num2);
    return 0;
}
```
#fahrenheit into digree celsius#
```c
#include<stdio.h>
#include<conio.h>
void main()
{
    float fahrenheit,celsius;
    printf("\n enter the temperature in fahrenheit:");
    scanf("%f",&fahrenheit);
    celsius=(0.56)*(fahrenheit-32);
    printf("Temperature in digree celsius=%f",celsius);
    return 0;
}

```
#simple calculate#
```c
#include<stdio.h>
#include<conio.h>
void main()
{
    int a,b,c,d,total_amt;
    printf("enter coin of 10:");
    scanf("%d",&a);
    printf("enter coin of 5:");
    scanf("%d",&b);
    printf("enter coin of 2 :");
    scanf("%d",&c);
    printf("enter coin of 1:");
    scanf("%d",&d);
   total_amt=a*10+b*5+c*2+d*1;
   printf("total amt%d",total_amt);
    return 0;

}

#person eligible vote#
```c
#include<stdio.h>
#include<conio.h>
void main(){
int age;
printf("enter the age");
scanf("%d",&age);
if(age>=18)
{
    printf("you can vote");
}
else
    {



    printf("not vote");

}
return 0;
}

```
#determine the character entered by the user#
```c
#include<stdio.h>
#include<conio.h>
void main()
{
     char ch;
     printf("enter any key");
     scanf("%c",&ch);
     if(isalpha(ch)>0)
        printf("\nthe user has entered a character");
     if(isdigit(ch)>0)
        printf("\n the user has entered a digit");
     if(isprint(ch)>0)
        printf("\nthe r has printable character");
     if(ispunct(ch)>0)
        printf("\n the user has entered a punctuation mark");
     if(isspace(ch)>0)
        printf("\n the user has entered white space character");
     return 0;
}
```
#entered character in lower case then covert into upper case if entered character in upper case then covert into lower case#
```c
#include<stdio.h>
#include<conio.h>

void main()
{
   char ch;
   printf("enter the character");
   scanf("%c",&ch);
   if(ch>="A" && ch<="Z")
   {
       printf("\n the entered character was in upper case%c",(ch+32));
   }
   else{
    printf("\n the entered character was in upper case%c",(ch-32));
   }

}
```