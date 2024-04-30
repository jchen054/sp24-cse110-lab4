1. 3 is printed. Because i is intialized using var, it can be accessed outside the code block ofthe for loop.
2. 150 is printed. Because discountedPrice is intialized using var, its final value 150 can be accessed outside the code block of the for loop.
3. 150 is printed. Because finalPrice is intialized using var, its final value 150 can be accessed outside the code block of the for loop.
4. The function will return \[50,100,150\]. This is the modified array after the operations in the for loop.
5. An error occurs because i is intialized using let, and cannot be accessed outside the code block of the for loop.
6. An error occurs because discountedPrice is intialized using let, and cannot be accessed outside the code block of the for loop.
7. 150 is printed. This is the final value of finalPrice, which can be accessed by line 14 because it was intialized earlier in the same code block.
8. \[50,100,150\] is returned. Because discounted is intialized using let earlier in the code block, it can be accessed and returned at the end of the function.
9. An error occurs because i is intialized using let, and cannot be accessed outside the code block of the for loop.
10. 3 is printed. This is the value of the length of the prices array and can be accessed in the same code block.
11. \[50,100,150\] is returned. This is the modified prices array, which can be accessed and returned in the same code block.
12.
````
a) student.name
b) \student\["Grad Year"\]
c) student.greeting()
d) student["Favorite Teacher"].name
e) student.courseLoad[0]
````
13.
````
a) 32, 2 is converted to '2' and concatenated with '3'
b) 1, '3' is converted to 3 and 2 is subtracted from 3
c) 3, null is converted to 0
d) 3null, null is converted to 'null' and concatenated with '3'
e) 4, true is converted to 1
f) 0, false is converted to 0 and null is converted to 0
g) 3undefined, undefined is converted to 'undefined' and concatenated with '3'
h) NaN, '3' is converted to 3 and undefined is converted to NaN, resulting number is NaN
````
14. 
````
a) true, '2' is converted to 2, 2 > 1
b) false, '1' comes before '2' in ASCII code
c) true, '2' is converted to 2, 2 == 2
d) false, 2 is a number and '2' is a string
e) false, true is converted to 1, 1 != 2
f) true, Boolean(2) is converted to true and true === true
````
15. == compares two values and converts them to numbers if they are not the same type; === is strict equality and compares two values for type and value
17. [2,4,6] is returned. The function declares a new array, then loops through all elements in the input array and calls callback, the function doSomething, which multiplies the value by 2 and stores it in the returned array.
19. 1 4 3 2