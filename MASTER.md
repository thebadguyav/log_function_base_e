#include<stdio.h>
#include<math.h> //header file for log() function
int main()
{
    int a; //variable whose log is to be calculated
    float ans=0.0; //variable for storing the log value
    printf("Enter the number:");
    scanf("%d",&a);
    ans=log(a);
    printf("The logarithmic value of the entered integer is: %f",ans);
return 0;
}
