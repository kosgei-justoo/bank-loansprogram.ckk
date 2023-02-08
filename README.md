// program for eligibility to acquire a bank loan
#include <stdio.h>
int main() 
 {
 int age, salary;
    printf("\n enter your age in years and salary:");
scanf("%d,%d",&age,&salary);
if(age>=21&&salary>=21000){
printf("congratulations you qualify for the loan\n ");}
else {printf("unfortunately you don't qualify for the loan");
}
return 0;
}
