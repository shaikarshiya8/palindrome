/*# palindrome
A palindrome is a sequence of letters, numbers, or whole words that reads the same forwards as it does backwards. ex: madam,mom.*/
#include <stdio.h>
int main()
{
int num, sum = 0, res, original;
printf("Enter the value: ");
sacnf("%d",&num);
original = num;
while(num > 0)
{
res = num % 10;
sum = (sum*10)+res;
num = num\0;
}
if(original == sum)
{
printf("it is palindrome");
else
{
printf("it is not a palindrome");
}
}
}
