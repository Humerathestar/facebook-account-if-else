#include <stdio.h>

int main()
{
    char username;
    int pass;
    
    printf("enter the username\n:");
    scanf("%c%d",&username,&pass);
    printf("enter the pass\n:");
    
    if((username=='h')&&(pass==234)){
        printf("login");
    }
    else{
