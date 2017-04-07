# Lab-Assignment-5
//Collect First and Last names along with Salaries.

/*

Programer: John Johnston

Chapter: 5

Assignment: 5

Date: 04/07/2017

Description:

Input:
1.

Output:
1.

*/

#define _CRT_SECURE_NO_WARNINGS

#include <stdio.h>
#include <string.h>


int main(void)
{  //start function main

	int intSalaryArray[50][50];
	char charFNameArray[50][50];
	char charLNameArray[50][50];
	int intSalarySum = 0;
	int intSalaryAvg = 0;
	int i;

	for (i = 0; i < 50; i++)
	{
		printf("Please enter a first name for Teacher %d: \n", i + 1);
		scanf("%s", charFNameArray[i]);

		// this is where I've tried the different methods
		
		printf("Please enter a last name for Teacher %d: \n", i + 1);
		scanf("%s", charLNameArray[i]);
		printf("Please enter a Salary for Teacher %d: \n", i + 1);
		scanf("%d", intSalaryArray[i]);
		

	}
