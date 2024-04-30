13. Arithmetic
A. '3' + 2 yields '32'. Integers map to their exact string representation so we just concatenate 3 and 2 as strings.
B. '3' -2 yields 1. Here as we are doing subtraction, 3 is converted to its integer type so we are doing a subtraction operation on 3 and 2, yielding 1.
C. 3 + null yields 3, as since 3 is passed as an integer, null just corresponds to 0 and 3+2 = 0..
D. '3' + null yields '3null'. Here '3' is a string and with the + operation, null gets converted to its string equivalent which is just the string null and we perform the concatenation operation.
E. true + 3 results in 4. We are doing integer addition and the boolean true takes the integer value of 1, so we do 3 + 1, which is 4.
F. false + null = 0. This is also integer addition. Since false takes the value of 0 and null is also 0, we are left with 0.
G. '3' + undefined results in '3undefined'. Here, we perform string concatenation so undefined just becomes "undefined". 
H. '3' - undefined results in NaN. Here, with the minus sign the 3 gets converted to the integer 3 and we do subtraction. However, undefined has no mathematical value so we get NaN.

14. Comparison
A. True. Here we are comparing a string with an integer, so the string becomes an an integer. 2 is greater than 1, so we get true.
B. '2' < '12' is false. Here we are comparing two strings with each other by their numerical or lexicographical order. 2 has a higher order than 1 for strings, so this is false.
C. True. The double equality sign means the equality test. This is also a comparison so the string '2' becomes a 2. 2 is equal to 2, so true.
D. False. Three equal signs means a strict equality check, so type i taken into account. The integer and string 2 are two different types, so this returns false.
E. False. We are doing equality comparison for integers, and since true is 1 and 1 is not equal to 2, this is false;
F. True. This is a strict equality check, and Boolean(2) returns true. Left and right hand side are both same value and type, so it returns true.

15. The difference between == and === is the specificty to which the equality check is carried out. For ==, we only care about the value on left or right instead of the type. Comparatively, for ===, the type and values both have to match with each other. == does conversions in the case of comparisons and evaluations.

16. check JS file 

17. The result for this will be an array with the elements 2, 4, and 6. The logic for this comes from how callback function is being invoked. doSomething takes in a num and multiplies it by 2. In the modifyArray function, we push the value of doSomething applied to 1, 2, and 3.
  
18. check JS file 

19. The code above outputs:
    1
    4
    3
    2
