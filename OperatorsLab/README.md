# Operators
 
  Operators are tools that allow us to use operations on variables. A variable can be created by combining two other variables via an operation or by
 declaring numbers or text and combining them with operators
 You've seen operators before, the basic ones we use are
     
      + : addition
      - : subtraction
      / : division
      * : multiplication
      % : modulous

Swift has a dedicated remainder operator in the form of %, and it’s used to return the remainder after dividing one number wholly into another. For example, 14 % 3 is 2, because you can fit four 3s into 14, and afterwards you have the remainder 2.
 
 Below are some operations that combine operators and variables, try to copy/paste this into your console and view the output
     
         var a = 10
         a = a + 1
         a = a - 1
         a = a * a
 
 There is also the possibility to quickly do an operation and set the value, using a combination of an operator and equals sign
 += : this is a COMPOUND operator, which means that a variable will be plus equaled whatever is after the equal sign
  
        var a = 0
        print(a)
        0
        var a += 10
        print(a)
        10
         
 This can be used with other operators, try seeing the output of the operators below
 
         var b = 10
         print(b)
         b += 10
         print(b)
         b -= 10
         print(b)
 
