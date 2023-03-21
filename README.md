#include <stdlib.h>    
#include <stdio.h>    
    
int main(){    
    int n,sum=0; //定義兩個變數，一個是變數n，另一個是變數sum，初始值為0   
    scanf("%d",&n); //讀取輸入的整數值   
    for(int i=1;i<=n;i++){ //1到n中，所有可以被3整除的數字相加，得到它們的總和。   
        if(i%3==0){    
            sum+=i;    
        }    
    }    
    printf("%d\n",sum); //顯示總和   
}  
