1. i is printed because although it was declared in the for loop, it was declared as a var which is a global variable and therefore, it exists outside of the for loop
2. discountedPrice is printed because although it was declared in the for loop, it was declared as a var which is a global variable and therefore, it exists outside of the for loop
3. finalPrice is printed because it was declared outside of the for loop and declared as a var making it a global variable that exists outside of the for loop
4. [50, 100, 150], .5 means 50% discount so each discounted price is half the original price rounded to the second decimal place; each finalPrice is pushed to the discounted array which is a global variable
5. error because i was declared using let within the for loop so it only exists within the for loop
6. error because discountedPrice was declared using let within the for loop so it only exists within the for loop
7. finalPrice is printed because it was declared outside of the for loop making it a global variable that exists outside of the for loop
8. [50, 100, 150], .5 means 50% discount so each discounted price is half the original price rounded to the second decimal place; each finalPrice is pushed to the discounted array which is a global variable
9. error because i was declared using let within the for loop so it only exists within the for loop
10. error because discountedPrice was declared using const within the for loop so it only exists within the for loop
11. finalPrice is printed and has a value of 0 because it was declared as a const so it's value can't be changed
12. [], discounted was declared as a const meaning that it's value can't be changed. Since it was initialized as [], that is the value that will be returned
13. Data types
    A. student.name
    B. student['Grad Year']
    C. student.greeting
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
14. Arithmetic
    A. '32'; + can be a mathematical function or it can indicate string concatenation so 2 is converted to a string since '3' is a string and then they are string concatenated
    B. 1; - can only be a mathematical function so both '3' and 2 are converted to numbers which gives 3-2 which equals 1
    C. 3; null doesn't have a value so since 3 is a number, + is interpreted as a mathematical function and null = 0 and 3 + 0 = 3
    D. '3null'; null doesn't have a value so since 3 is a string, + is interpreted as string concatenation and null is converted to a string 'null'. '3' + 'null' = '3null'
    E. 4; Since 3 is a number, + is interpreted as a mathematical function so true is converted to a number. true = 1 and 1 + 3 = 4
    F. 0; Since null doesn't have a data type and booleans can't be added, + is interpreted as a mathematical function and since false = 0 and null = 0, 0 + 0 = 0
    G. '3undefined'; undefined doesn't have a data type so since "3" is a string, + is interpreted as a string concatenation. Therefore, undefined is converted to a string 'undefined' and '3' + 'undefined' = '3undefined'
    H. NaN; Since - can only be a mathematical function, both "3" and undefined are converted to numbers. 3 - NaN = NaN
15.  Comparison
     A. true; Since they are different types, both '2' and 1 are converted to numbers and 2 > 1 is true
     B. false; Since they are the same data types, the first character in each string is compared. '2' > '1' so '2' is > '12'. '2' < '12 is false
     C. true; Since they are different types, they are converted to numbers and 2 == 2 is true
     D. false; Since === is used, it is comparing without type conversion and 2 is not equal to '2'
     E. false; Since they are different types, they are converted to numbers and true = 1. 1 is not equal to 2
     F. true; Boolean(2) = true and true === true
16.  == checks for equality with type conversion while === checks for equality without type conversion
17.  'How are you?'; 2 == true is false because true is converted into a number, true = 1, and 2 is not equal to 1. The next else if statement is 2 which is converted to a boolean and non-zero number = true. Therefore, 'How are you?' is printed.
18.  see JS file
19.  [6, 8, 10]; doSomething is passed into modifyArray as callback so when callback is called on line 4, it's passing array[i] and function(x) into doSomething. That means that on line 12, callback equation is function(x). num+2 is passed in as x so [3,4,5] respectively for each element in the input array. Then, the function returns x*2 which is [6,8,10]. Each value is pushed to newArr as the for loop runs and [6,8,10] is the returned newArr.
20.  see JS file
21.  1
     4
     3
     2
     