## Operators and Loops ##

### comparisopn operators:Evaluating condition :
- you can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be Boolean: TRUE or FALSE.

operator | what is this  | meaning example 
---------|----------|---------|-------------
== | (is equal to) | comparing two values and see if they are the same |'hello' == 'yes' -->False but 'hello' == 'hello'---> true
===|strict equal |comparing two operators and check if that both the data type and value are the same | '3'===3 --->false but '3' === '3'--->true
!= | Not equal | comparing two values and see if they are not the same |'hello' != 'yes' -->True but 'hello' != 'hello'---> false
!==|strict not equal | comparing two operators and check if that both the data type and value are not the same | '3'!==3 --->True  but '3' !== '3'--->False 
 `>` | greater that | check if the number in left is *greater* than the number in right | 7>5 ----> true , 3>5 ---> false 
< | less than |check if the number in left is *less* than the number in right | 4<5 ----> true , 7<5 ---> false 
`>=`| greater than or equal| check if the number on the left is *greater than or equal* to the number in the right| 4>=3 --> True , 3>= 4 --> false ,3>=3 --> true
<= | less than or equal| check if the number on the left is *less than or equal* to the number in the right| 4<=3 --> True  , 3<= 4 --> true  ,3<=3 --> true

### Logical operator ###
Its allow to compare the result of more than one comparison operator 

1. && (AND) :when used with Boolean values, && returns true if both operands are true; otherwise, returns false.
1. `|| (OR) :when used with Boolean values, || returns true if either operand is true; if both are false, returns false.`
1. NOT (!) : Returns false if its single operand that can be converted to true; otherwise, returns true.

## For And While Loop ##
- A loop is a sequence of instructions that is continually repeated until a certain condition is met in computer programming.
 
1.  ### For loop ### :
** Syntax: **
for (statement 1; statement 2; statement 3){
 execute code block
}
    - Statement 1 is executed once before the code block is run.
    - Statement 2 defines the condition needed to execute the code block.
    - Statement 3 is executed every time the code block is run.

 2. ### While loop ###
   Syntax :
  while (condition){
 execute code block
}
- The code block will continue to loop as long as the condition is true.


