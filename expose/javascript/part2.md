1. Output at line 12 will be 3. Since i is initialized with "var" it can be accessed outside the for loop.
2. Output at line 13 will be 150. Since discountedPrice is initialized with "var" it can be accessed outside the for loop.
3. Output at line 14 will be 150. Since finalPrice is initialized with "var" it can be accessed anywhere in the function.
4. This function returns [50,100,150]. The function returns the discounted prices with discount 0.5.
5. Error. Since i is initialized with "let" its scope is only the for loop block. Thus accessing it outside the block is not possible giving an error
6. Error. Since discountedPrice is initialized with "let" its scope is only the for loop block. Thus accessing it outside the block is not possible giving an error
7. Output at line 14 will be 150. Since finalPrice is initialized with "let" but at the top of the function it can be accessed anywhere in the function.
8. This function returns [50,100,150]. The function returns the discounted prices with discount 0.5. Since it is initialized with "let" but at the top of the function it can be accessed anywhere in the function.
9. Error. Since i is initialized with "let" its scope is only the for loop block. Thus accessing it outside the block is not possible giving an error
10. Output at line 12 will be 3. Since length is initialized with "const" it can be accessed in the function. 
11. This function returns [50,100,150]. The function returns the discounted prices with discount 0.5. Even though const is used for discounted we are never reassigning discounted just updating values in the array.
12. 
    a) student.name 
    b) students["Grad Year"]
    c) student.greeting()
    d) student["Favorite Teacher"].name
    e) student.courseLoad[0]
13. 
    a) '32'
    b) 1
    c) 3
    d) '3null'
    e) 4
    f) 0
    g) '3undefined'
    h) NaN
14. 
    a) true
    b) false
    c) true
    d) false
    e) false
    f) true

15. "==" checks value, "===" checks value and type both.
16. The function returns [2, 4, 6] because it applies the doSomething function (which doubles a number) to each element of the array and stores the results in a new array.
17. The output is 1 4 3 2 because 1 and 4 run immediately, 3 runs next from the event queue (after 0ms), and 2 runs last after a 1-second delay.