# Pointers--Call-by-value-and-call-by-reference
## AIM
To perform swap operation by call by value and call by reference(using pointers)
## Theory 
In call by value method, the value of the actual parameters is copied into the formal parameters. In call by value method, we can not modify the value of the actual parameter by the formal parameter whereas in call by reference, the address of the variable is passed into the function call as the actual parameter.The value of the actual parameters can be modified by changing the formal parameters since the address of the actual parameters is passed.
## Algorithm  
void swap (int *a, int *b)  
    int temp;   
    temp = *a;  
    *a=*b;  
    *b=temp;  
    print a and b
in main we pass adress of a and and b> &a and &b
## Conlusion
Call By Value- Changes made inside the function is limited to the function only. The values of the actual parameters do not change by changing the formal parameters.
Call By Reference- Changes made inside the function validate outside of the function also. The values of the actual parameters do change by changing the formal parameters.
