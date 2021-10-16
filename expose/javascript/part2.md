1. Line 12 prints 3.
2. Line 13 prints 150.
3. Line 14 prints 150.
4. The function returns the array [50, 100, 150].
5. The code causes an error because i is only avaialable locally and is out of scope outside of the for loop.
6. Similar to number 5, since discounterPrice is initialized using <em>let</em>, the variable can only be called inside the for loop. This code results in an error.
7. At line 14, the finalPrice is printed, which is 150 in this case. This is allowed since finalPrice is initialized at the top of the function, allowing it to be called and used throughout the function.
8. This function returns the array [50, 100, 150]. The for loop iterates through the original array, applying the discount and rounding the numbers, and adds the discounted price to a new array. This is returned at the end of the function.
9. The code causes an error because i cannot be accessed outside of the for loop. This is because i is initialized inside the for loop using let.
10. At line 12, **3** is printed since it is the length of the array.
11. The function returns the array [50, 100, 150]. This is because the function loops through the original prices array and applys the discount, which is 50% in this case. The new values are stored in an array that is returned.
12. a. student.name	b. student["Grad Year"] 	c. student.geeting()	d. student['Favorite Teacher'].name	e. student.courseLoad[0]
13. Arithmetic
a. '32', string concatenation so 2 is converted to a string
b. 1, integer subtraction
c. 3, null acts as 0
d. 3null, string concatenation so null is converted to a string
e. 4, true is a numeric 1
f. 0, since both false and null are numeric 0s.
g. '3undefined', string concatentation so undefined is converted to a string
h. NaN, since undefined is of type NaN and numeric operations are not possible
14. Comparison
a. true, since '2' becomes a number 2
b. false, since the strings are compared and '2' > '1'
c. true, since '2' becomes a number 2
d. false, because === checks for type equality.
e. false, since true is a numeric 1 and 1 != 2
f. true, since Boolean(2) evaluates to a true.
15. Double equals checks if either of the variables used are equal without looking at their types. Triple equals checks the equality without type conversion.
17. The result is that an array with the values [2, 4, 6] is returned. This is because the original array is looped through and the values are passed to the function doSomething() where the numbers are doubled and inserted into a new array.
19. The output of the code is numbers 1 4 3 2.
