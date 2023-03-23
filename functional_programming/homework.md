# Task 1: Thoughts? 
How would you rate coding in Racket from a scale of 1 to 5? 
In your opinion, how does coding in Racket compare to coding in Java or Python? 
Do you find Racket’s syntax and approach more or less intuitive than those of the other languages?
Explain your reasoning and provide examples to support your views.

On a scale of 1 to 5 - I would rate it a 4 or 5.
It is very simple and straightforward , though not as intuitive. However, once you get the hang of the syntax, I find it wasy to work with. Additionally, 
the Dr/ Racket environment makles it wasy to find errors through highlighting. When I missed closing parentheses, it wouldn't highlight the entire line, and I knew I had to go back and check it. The visual was really helpful.  
For example, the HW for the explorer level looked as it does below is simple.

#### this is the python version (roughly) for adding

def addNum(num1, num2):   
    print(num1 + num2)   
addNum(2, 4)   


#### This is racket
;define a number   
(define num1 5) ;val num1 is 5   
(define num2 10) ;val num2 is 10   

(define add-numbers (+ num1 num2 )) ; + is a function, call it here   
add-numbers   

### Conclusion
While there are slightly less steps for python, the syntactical nature makes sense in how it works for racket. 


# Task 2: The Code
Define a variable called ‘num1’ and assign it the value 5.
Define another variable called ‘num2’ and assign it the value 10.
Create a function called ‘add-numbers’ that takes ‘num1’ and ‘num2’ as arguments and returns their sum. 
Test  the ‘add-numbers’ function by calling it with ‘num1’ and ‘num2’ as arguments and printing the result. 
Apply the same approach to create a function called ‘double’ that takes an integer as its input and returns twice the value of that integer. Then use this function to print the value of ‘double 5

## code  below

```#lang racket ; use the racket lang

(provide (all-defined-out)) ; make all functions available


;create add-numbers
;define a number
(define num1 5) ;val num1 is 5
(define num2 10) ;val num2 is 10

(define add-numbers (+ num1 num2 )) ; + is a function, call it here
add-numbers

;define integer value
(define integer 5)
;create double function
(define double (* integer 2)) ; creates doubling function
;call doubling integer
double 
