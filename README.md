# binaryone
#include <stdio.h> 
int main() 
{ 
   int n,count=0;
   scanf("%d",&n); 
   while(n>0) 
   { 
      if((n/2)*2 != n) 
      { 
        count++; 
      } 
      n=n/2; 
   } 
   printf("%d",count); 
}
