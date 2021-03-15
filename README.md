# Programming Project 2 <img src="man/figures/logo.png" align="right" alt="" width="120" />

> Programming Project 2 aims to generate a Recursion Tree. The algorithm will accept as input 
> the following recurrence functions:
> 
> Divide-And-Conquer: T(n) = aT(n/b) + f(n) where
> a is an integer that is >= 1
> b is a rational number > 1
> 
>Chip-and-Be-Conquered: T(n) = aT(n - b) + f(n)
>a is an integer that is >= 1
>b is an integer > 0
>
>f(n) is a polynomial cn^d:
>0 < c < infinity where c is a rational number
>0 < d < infinity where d is a rational number

## Project Requirements

An algorithm will be defined using pseudocode.
The worst-case running time will be determined.
Assignment requirements included:

  1. Generating a recursion tree in DAC or CABC forms.
  2. Generate a depth of at least 0, 1, 2, and 3.
  3. Output Recursive Cost, Nonrecursive Cost of each node
  4. Output Total Nonrecursive Cost.
  5. Fractions must be represented in LCD.
  
## Compiling Instructions
IDE used - Eclipse / Compiler used - JDT / Programming Language - Java
> Instructions to run code: 
  1. Open the .java programs on Eclipse (ImprovedRecTree.java, Rational.java, RationalNumbers.java)
  2. click on the Run button for ImprovedRecTree.java
  3. Input integer 1 or integer 2 for D&C or CABC
  4. Input a, b, c, d values accordingly.
  5. Console will output resulting Recursion Tree.

## List of Files in Submission:
Programming-Project-2 includes 
1. Two .java files (ImprovedRecTree.java, Rational.java)
2. Algorithm written in pseudocode (.PDF)



