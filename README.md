## PLP3

#### 1. What are the boolean values in your language? (e.g., True and False, true and false, 1, and 0,  etc)
###### struct "Bool", which explicitly represents boolean values in Swift, is a value type that is either "true" or "false". Only simple boolean values are used in Swift to prevent errors. The values 0 and 1 are strictly int types and not convertible. 
*         Example:
          var godotHasArrived = false
 
          let numbers = 1...5
          let containsTen = numbers.contains(10)
          print(containsTen)
          // Prints "false"
      
          let (a, b) == (100, 101)
          let aFirst = a < b
          print(aFirst)
          // Prints "true"
#### 2. What types of conditional statements are available in your language? (if/else, if/then/else,  if/elseif/else). Does your language allow for statements other than “if” (for example, Perl has an “unless” statement, which does the opposite of “if”!)? What operators are used to act on booleans?
###### Swift uses some different conditional statements:
* if/elseif/else
*           \\Example:
            if <#condition 1#> {
             <#statements to execute if condition 1 is true#>
          } else if <#condition 2#> {
             <#statements to execute if condition 2 is true#>
          } else {
             <#statements to execute if both conditions are false#>
          }
