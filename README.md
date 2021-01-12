# C-Scientific-B-Scientific



#include<stdio.h>
#include <conio.h>
#include <math.h>
#include <stdlib.h>
int main(void) 
{
    int Choice , i , a , b ;
    float X,Y, result;
    
    do{
        printf("\n Select your operation ( 0 to exit) :\n ");
        printf(" 1. Addition \n 2. Subtraction \n 3.Multiplication \n 4. Division\n");
        printf("5. Square root \n 6. X ^ Y \n 7. X^2 \n 8. X ^ 3 \n ");
        printf("9. 1/x \n 10. X ^ (1/Y) \n 11. X^ (1/3) \n ");
        printf(" 12. 10 ^ X \n 13. X! \n  15. log10(X) \n  ");
        printf(" 16. sin (X) \n 17. cos(X) \n 18. tan(X) \n 19. cosec(X) \n 20. sec(X) \n 21. cot(X) \n");
        printf("Choice : ");
        scanf("%d", &Choice);
        if(Choice == 0 ) exit(0);
        
        switch(Choice)
        {
            
            case 1: 
            printf("Enter X : " );
            scanf("%f" , &X );
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result = X + Y;
            printf("\n result : %f ", result );
            break;
             case 2: 
            printf("Enter X : " );
            scanf("%f" , &X );
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result = X - Y;
            printf("\n result : %f ", result );
            break;
           
            case 3: 
            printf("Enter X : " );
            scanf("%f" , &X );
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result = X * Y;
            printf("\n result : %f ", result );
            break;
           
            case 4: 
            printf("Enter X : " );
            scanf("%f" , &X );
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result = X / Y;
            printf("\n result : %f ", result );
            break;
            
            case 5 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  sqrt(X);
            printf("\n result : %f " , result );
            break;
           
           
           /* case 6 :
            printf("Enter X : " );
            scanf("%f" , &X );
            
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result =  X ^ Y ;
            printf("\n result : %f " , result );
            break; */
            
            case 7 :
            printf("Enter X : " );
            scanf("%f" , &X );
            
            result =  X ^ 2;
            printf("\n result : %f " , result );
            break;
            
            case 8 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  X ^ 3;
            printf("\n result : %f " , result );
            break;
            
            case 9 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result = 1 / X ;
            printf("\n result : %f " , result );
            break;
            
            case 10 :
            printf("Enter X : " );
            scanf("%f" , &X );
            
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result =  X ^ ( 1 / Y);
            printf("\n result : %f " , result );
            break;
            
            case 11 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result = X ^ ( 1/3);
            printf("\n result : %f " , result );
            break;
            
            case 12 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  10 ^ X;
            printf("\n result : %f " , result );
            break;
            
            case 13:
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  X!;
            printf("\n result : %f " , result );
            break;
            
            case 14:
            printf("Enter X : " );
            scanf("%f" , &X );
            printf("Enter Y : " );
            scanf("%f" , &Y );
            result =  X % Y;
            printf("\n result : %f " , result );
            break;
            
            case 15 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  log10(X);
            printf("\n result : %f " , result );
            break;
            
            case 16 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  sin(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            
            case 17 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  cos(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            
            case 18 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  tan(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            
            case 19 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  1 / sin(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            
            case 20 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  1 / cos(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            
            case 20 :
            printf("Enter X : " );
            scanf("%f" , &X );
            result =  1 / tan(X * 3.14159/180);
            printf("\n result : %f " , result );
            break;
            default : 
            printf(" invalid Choice !");
        }
    }
    while(choice);
    getchar();
    return 0;
}

    
            
            
        
   
    
    
