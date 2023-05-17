## Write a pseudocode for accepting radius and calculate the area of the circle.
```
begin
numeric r,area
accept r
area=3.14*r*r
display area
end

```

## Write a pseudocode for accepting a number and display the multiplication table of the given number.
```
begin
accept n,i
for (i=1;i<=10;i++)
{
    n*i
}
display 
end
```






## pseudocode for checking whether given number is perfect number or not.
```
begin
numeric n,i
accept n
for (i=1;i<n;i++)
{
    if (n%i==0)
    {
        sum=sum+i
    }

}
if (n==sum)
diplay it is a pefect number
else
display it is not a perfect number
end
```

## pseudocode for accepting three numbers and display the lowest number out of three numbers.

```
begin
numeric num1,num2,num3
accept num1,num2,num3
if(num1 < num2 && num1 < num3)
	{
		display "num1 is the smallest"
	}
	else if(num2 < num3 && num2 < num1)
	{
		display "num2 is the smallest"
	}
	else
	{
		display "num3 is the smallest"
	}	
end
```

## Write a pseudocode to swap two numbers without using third variable.
```
begin
accept x, y
display x, y
 x = x + y
 y= x - y
x =x - y
display x, y
 END
```
 ##  Write a pseudocode for accepting a number and check whether number is perfect square or not.
 ```
 begin
 numeric num,c
 display"enter the number"
 accept the number
 for (c=0;c*c=<num;c++)
 {
	 if
	 {
        (num%c==0)&&(num/c==num)
		 display the number is a perfect square 
	 }
	 else
	 {
		 display the number is not a perfect square
	 }
 }
end
```


## Write a pseudocode for accepting a number from 1 to 7 and display the name of the week.

```
begin
ACCEPT THE NUMBER FROM 1 TO 7
IF N >7 
DISPLAY "INVALID DAY"
ELSE IF N=1
DISPLAY " MONDAY"
ELSE IF N=2
DISPLAY"TUESDAY"
ELSE IF N=3
DISPLAY "WEDNESDAY "
ELSE IF N=4
DISPLAY " THURSDAY "
ELSE IF N=5
DISPLAY " FRIDAY "
ELSE IF N=6
DISPLAY " SATURDAY "
ELSE
DISPLAY" SUNDAY "
end
```


## Write a pseudocode for implementing the concept of menu driven calculator which will accept two numbers and perform the calculation based upon users choice like (+,-,*,/).
```
begin
ACCEPT TWO NUMBERics num1,num2
DISPLAY ENTER YOUR CHOICE
ACCEPT USER CHOICE
CHOOSE AN OPTION
1-ADDITION
2-SUBTRACTION
3-MULTIPLICATION
4- DIVISION
DISPLAY THE RESULT
end
```


## Write a pseudocode for accepting firstname,middlename and lastname from the user in three different variables and concatenate the first character of firstname with second character of middlename and third character of lastname.
```
begin
accept  VARIABLES X,Y,Z,A,B
ACCEPT FIRST NAME FROM USER INTO VARIABLE X
ACCEPT MIDDLE NAME FROM USER INTO VARIABLE Y
ACCEPT LAST NAME FROM USER INTO VARIABLE Z
A = FIRST CHARACTER OF VARIABLE X + SECOND CHARACTER OF VARIABLE Y + THIRD CHARACTER OF LAST NAME
B = A
B = DISPLAY THE RESULT
end

```

## Write an pseudocode for accepting a five digit number and check whether the number is palindrome or not.
```
begin
a=accept a number
b= reversal of a
if(a=b)
the number is palindrome
else
the number is  not a palindrome
end
```


## Write a pseudocode for displaying the list of prime numbers in given range.
```
begin
numeric num1,num2,i,j
for (i=num1;i<=num2;i++)
{
    for (j=2;j<=i;j++)
    {
        if(i%j==0)
    }
}
display the list of prime numbers in given range
end
```


## Write a pseudocode to accept student Details like (StudentID, StudentName, StudentAge, Marks1, Marks2,Marks3) Calculate Total and Percentage. If percentage is greater than 50 then display “PASS” else display “FAIL”.
```
begin
numeric marks1,marks2,marks3,TOTAL,PERCENTAGE
display student id
accept student id
display student name
accept student name
display student age
accept student age
display student marks1
accept student marks1
display student marks2
accept student marks2
display student marks3
accept student marks3
total = marks1+marks2+marks3
percentage = (total /300)*100
if percenatge > 50
display pass
else
display fail
end
```