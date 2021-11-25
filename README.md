#include<stdio.h>
#include<string.h>
void main()
{
    char str1[20],str2[20];
    int v;
    printf("Enter strings ");
    scanf("%s",&str1);
    scanf("%s",&str2);
    v=strcmp(str1,str2);
    if(v==0)
    printf("\nsame");
    else 
    printf("\n Not same");
}
