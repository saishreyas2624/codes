multiline comment

/* Online C compiler to run C program online
 it stores it in int age variable */
#include <stdio.h>

int main() {
    int age;
    
    printf("enetr the input:");
    scanf("%d",age);
    
    printf("age=%d",age);

    return 0;
    }


    ELSE CODES
    #include <stdio.h>
int main(){

int age =19;

if(age >=18){
    printf("you are eligibl to vote ");
}

else{
    printf("you are not eligible to vote");
}
return 0;
}



SWITCH WITH MULTIPLE CASES
#include <stdio.h>
int main(){
    
    int number;
    printf("enter your value : ");
    scanf("%d" , &number);
    
    switch(number){
    case 1:
    case 2:
    case 3:
    case 4:
    printf("weekdays");
    break;
    
    case 5:
    case 6:
    printf("weekends");
    break;
    
    default:
    printf("invalid number");
    
    return 0;
    }
}
