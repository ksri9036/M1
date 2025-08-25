
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include <stdio.h>

int main() {
  char char1, char2, char3;

  printf("Enter the first character: ");
  scanf(" %c", &char1); // Note the space before %c to consume any leading whitespace

  printf("Enter the second character: ");
  scanf(" %c", &char2);

  printf("Enter the third character: ");
  scanf(" %c", &char3);

  printf("The characters in reverse order are: %c %c %c\n", char3, char2, char1);

  return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/bc3d76c4-cd60-43d8-acbe-7bb76e096bdf)

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
```
#include <stdio.h>

int main() {
  int A;

  printf("Enter a value for A: ");
  scanf("%d", &A);

  if (A > 0) {
    printf("%d is a positive number.\n", A);
  } else {
    printf("%d is not a positive number.\n", A);
  }

  return 0;
}
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/d2b67ff7-5f84-4605-bfe4-7b9beb66d5f0)

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
```
#include <stdio.h>

// Structure to represent a fraction
struct Fraction {
    int numerator;
    int denominator;
};

// Function to compare two fractions and return 1 if f1 > f2, -1 if f1 < f2, and 0 if equal
int compareFractions(struct Fraction f1, struct Fraction f2) {
    // To avoid potential overflow, we can compare cross-products
    long long val1 = (long long)f1.numerator * f2.denominator;
    long long val2 = (long long)f2.numerator * f1.denominator;

    return (val1 > val2) ? 1 : (val1 < val2) ? -1 : 0;
}

int main() {
    struct Fraction frac1, frac2, minimumFraction;

    printf("Enter the first fraction (numerator/denominator): ");
    scanf("%d/%d", &frac1.numerator, &frac1.denominator);

    printf("Enter the second fraction (numerator/denominator): ");
    scanf("%d/%d", &frac2.numerator, &frac2.denominator);

    // Ensure denominators are not zero
    if (frac1.denominator == 0 || frac2.denominator == 0) {
        printf("Error: Denominator cannot be zero.\n");
        return 1; // Indicate an error
    }

    // Compare the fractions using the ternary operator
    minimumFraction = (compareFractions(frac1, frac2) <= 0) ? frac1 : frac2;

    printf("The first fraction is: %d/%d\n", frac1.numerator, frac1.denominator);
    printf("The second fraction is: %d/%d\n", frac2.numerator, frac2.denominator);
    printf("The minimum fraction is: %d/%d\n", minimumFraction.numerator, minimumFraction.denominator);

    return 0;
}
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/8703fce2-acfc-41ba-a635-ef034efed159)

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
```
#include <stdio.h>

int main() {
  int inputValue;

  printf("Enter an integer value: ");
  scanf("%d", &inputValue);

  if (inputValue == 1) {
    printf("The input value is equal to 1.\n");
  } else {
    printf("The input value is not equal to 1.\n");
  }

  return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/8d643903-f31b-4041-81b1-110fe594c673)

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
```
#include <stdio.h>

int main() {
    int marks1, marks2, marks3, marks4, marks5, total;
    float percentage;
    
    // Input marks
    printf("Enter marks for Subject 1: ");
    scanf("%d", &marks1);
    printf("Enter marks for Subject 2: ");
    scanf("%d", &marks2);
    printf("Enter marks for Subject 3: ");
    scanf("%d", &marks3);
    printf("Enter marks for Subject 4: ");
    scanf("%d", &marks4);
    printf("Enter marks for Subject 5: ");
    scanf("%d", &marks5);

    // Calculate total
    total = marks1 + marks2 + marks3 + marks4 + marks5;

    // Calculate percentage
    percentage = (total / 500.0) * 100;

    // Display total and percentage
    printf("\nTotal Marks = %d\n", total);
    printf("Percentage = %.2f%%\n", percentage);

    // Determine division
    if (percentage >= 60) {
        printf("Division = First Division\n");
    }
    else if (percentage >= 45) {
        printf("Division = Second Division\n");
    }
    else if (percentage >= 33) {
        printf("Division = Third Division\n");
    }
    else {
        printf("Division = Fail\n");
    }

    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/1a49fe3b-ee9c-4c16-8a1f-7f054731b3aa)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

