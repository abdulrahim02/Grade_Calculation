# Grade_Calculation
Created by Abdulrahim Mulla


//Grade_Calculation
#include<stdio.h>
#include<stdlib.h>

int main()
{
	int m;
	printf("\t Bit Elemenyary School \n");
	printf("Enter the Marks:\n ");
	scanf("%d",&m);
	printf("Marks is %d \n",m);
 {
 	if(m<0 && m>100)
 	{
 		printf("Wrong Information about Marks\n");
	}
	else if(m>84 && m<=100)
	{			
		printf("Grade A");
	}
	
	else if(m>=70 && m<=84)
	{
		printf("Grade B");
	}
	
	else if(m>=55 && m<=69)
	{
		printf("Grade C");
	}
	
	else if(m>=40 && m<=54)
	{
		printf("Grade D");
	}
	else if(m>=1 && m<40)
	{
		printf("Grade F");
	}
 } 
	
	return 0;
}

