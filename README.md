// this code include the unit conversion
#include<stdio.h>
int main()
{
// 1. km to m
// 2. cm to m
// 3. farenheit to celcius
// 4. inch to foot
// 5. kg to g
// 6. gram to pound
  char input;
  int kmtom = 1000;
  int cmtom = 100;
  int inchtofoot = 0.0833333;
  int kgtog = 1000;
  int gramtopound = 0.00220462 ;
  printf("Enter the conversion number you want");
  scanf("%d",&i);
 while(1)
{
 printf("Enter the input character q to end");
switch(input)
 {
case 'q':
printf("Quiting the programme.....");
goto end;
default :
break;
 }
}
end;
return 0;
}
