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
###### Swift uses a few different conditional statements:
* if/elseif/else: (code execution based on one or more conditions)
*           Example:
            if <#condition 1#> {
             <#statements to execute if condition 1 is true#>
          } else if <#condition 2#> {
             <#statements to execute if condition 2 is true#>
          } else {
             <#statements to execute if both conditions are false#>
          }
* guard: (transfer of program control if one or more conditions are NOT met)
*           Example:
            guard <#condition#> else {
             <#statements#>
          }
* switch: (allows code execution depending on control expression)
*           Example:
            switch <#control expression#> {
          case <#pattern 1#>:
              <#statements#>
          case <#pattern 2#> where <#condition#>:
              <#statements#>
          case <#pattern 3#> where <#condition#>,
              <#pattern 4#> where <#condition#>:
              <#statements#>
          default:
              <#statements#>
          }
###### Operators used to act on booleans:
* ! - NOT (NOT inverts a boolean value, meaning, if the value was true, it will become false when used and vice versa)
* && - AND (AND combines two boolean values. If both are true, it will return true. Otherwise, it will return false)
* || - OR (OR combines two boolean values. If only one value is true, it will return true. Otherwise, it will return false)
#### 3. How does your programming language deal with the “dangling else” problem? 
###### The use of braces ({}) is enforced within Swift which deals with the dangling else issue. An if/else statement of any variation will not run without braces. 
#### 4. If your language supports switch or case statements, do you have to use “break” to get out of them? Can you use “continue” to have all of them evaluated?
###### As discussed earlier, Swift does support switch statements. "break" can be used to exit a loop, if statement, or a switch statement. 
*          Example:
            break
            break <#label name#>
###### "continue" is used in Swift, however, is not valid within a switch statement in Swift. It is only used within loops.
#### 5. Lastly, and perhaps most importantly: it is time to start thinking about what your programming project is going to actually be. In future sessions we will be breaking down your project into individual milestones for weekly check-ins. But for now, just write a short paragraph about what it is you are planning to code in your language of choice. Remember that it should be a substantial program - a game, app, calendar, web site, etc. (I'll try to dig up some examples to share before next class)
###### 
