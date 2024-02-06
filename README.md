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
