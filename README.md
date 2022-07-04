//Your task is to take two numbers of int data type, 
//two numbers of float data type as input and output their sum


#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main()
{
    
/*Step1 : Declare  variables: two of type int and two of type float.*/
    int num1, num2, int_sum, int_difference;
    float num3, num4, float_sum, float_difference;
    
   

    scanf("%d %d", &num1, &num2); // Input takes 2 integers 

    scanf("%f %f", &num3, &num4);  // Take 2 float data types  
 

    int_sum = num1 + num2; int_difference = num1 - num2;  // Add and subtract input 
   

    float_sum = num3 + num4; float_difference = num3 - num4; // Add and subtract input
    

    printf("%d ", int_sum); // Print int_sum and int_difference
    printf("%d\n", int_difference);// Print int_difference so screen 
 
    
// Print int_sum and int_difference scaled to 1 decimal place
    printf("%0.1f ", float_sum); 
    printf("%0.1f", float_difference);
    

    return 0;
}

