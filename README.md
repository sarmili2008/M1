
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
#include<stdio.h>
int main(){
    char c1,c2,c3;
    printf("enter first character: ");
    scanf("%c",&c1);
    printf("enter second character: "):
    scanf("%c",&c2);
    printf("enter third character: ");
    scanf("%c",&c3);
    printf("charater in reverse order: %c %c %c", c3, c2, c1);
return 0;
}
## OUTPUT:
enter first character:A
enter second character:B
enter trird character:C
characters in reverse order: C B A
















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
#include<stdio.h>
int main(){
     int a;
	 printf("enter a number: ");
	 scanf("%d",&a);
	 if(a>0){
	     printf("it is a positive number>\n");
		 }
	 else{
	 printf("it is not a positive number.\n");
	 }
	 return 0;
	 }
# OUTPUT:
enter a number: 5
it is a positive number.
enter a number: -3
it is not a positive number.










# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
#include<stdio.h>
int main(){
    int n1,d1.n2,d2;
	float f1,f2,res;
	printf("enter numerator of first fraction: ");
	scanf("%d",&n1);
	printf("enter denominator of first fraction: ");
	scanf("%d",&d1);
	printf("enter numerator of second fraction: ");
	scanf("%d",&n2);
	printf("enter denominator of second fraction: ");
	scanf("%d",&d2);
	f1 =(float)n1/d1;
	f2 = (float)n2/d2;
	res = (f1 < f2) ? f1 : f2;
	printf("the minimum between the two fraction is: %.2f\n",res);

	return 0;
	
}
## OUTPUT:
enter numerator of first fraction: 3
enter denominator of first fraction: 4
enter numerator of second fraction: 5
enter denominator of second fraction: 8
the minimum value between the two fractions is: 0.62







## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
#include<stdio.h>
int main(){
    int n;
	printf("enter a value: ");
	if(n==1){
	    printf("the input value is equal to 1.\n"):
	}
	else{
	    printf("the input value is not equal to 1.\n");
	}
	return 0;
}
## OUTPUT:
enter a value: 1
the input value is equal to 1.
enter a vlue: 5
the input value is not equal to 1.








	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
#include<stdio.h>
int main(){
     int m1,m2,m3;
	 float t,p;
	 printf("enter marks for subject 1: ");
	 scanf("%d",&m1);
	 printf("enter marks for subject 2: ");
	 scanf("%d",&m2);
	 printf("enter marks for subject 3: ");
	 scanf("%d",&m3);
	 t=m1+m2+m3;
	 p=t/3;
	 printf("total marks = %.2f\n",t);
	 printf("percentage = %.2f\n",p);
	 if(m1>=40 &&m2 >=40 && m3>=40){
	      if(p>=60){
		      printf("division = first");
		  }
		  else if(p>=48){
		     printf("division = second");
		  }
		  else if(p>=36){
		     printf("division = pass\n");
		  }
		  else{
		     printf("division = fail\n"0);
		  }
	 }
	 else{
	     printf("division = fail");
	 }
	 return 0;
}

## OUTPUT:
enter marks for subject 1: 70
enter marks for subject 2: 65
enter marks for subject 3: 60
total marks = 195.00
percentage = 65.00
division = first
## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

