# Code
prime numbers having 3 digits and starting with 5.

#include<stdio.h>  

void main(){    
    int n,i,m=0,flag=0;
    for(n=500;n<600;n++){
        flag=0;
        m=n/2;
        for(i=2;i<=m;i++){    
            if(n%i==0){   
                flag=1;    
                break;    
            }    
        }
        if(flag==0)    
            printf("%d\n",n); 
    }
}
