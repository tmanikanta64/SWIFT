# swift

* swift is a compiled programming language.
* swift is desighned by chris lattner.
* It was developed by Apple Inc for macOS,iOS,watchOS,tvOS,LinuX.
* code written at global scope is used as the entry point for the program,so we no need to use a main function.
* In swift we no need to write semicolons at the end of every statement.

### simple values

* Use let to make a constant and var to make a variable.

```swift
var myVariable = 4
myVariable = 16
let myConstant = 8
```

* A Constant or a variable must have the same type as the value you want to assign to it.
* However,you don't always have to write the explicitly.
* To download shift for windows visit https://swiftforwindows.codeplex.com/ .
* Providing a value when you create a constant or variable lets the compiler infer its type. In the example above, the   
   compiler infers that myVariable is an integer because its initial value is a integer.
* If the initial value doesn’t provide enough information (or if there is no initial value), specify the type by writing 
   it after the variable, separated by a colon.

```swift
let myVariable : double = 20.5
// explict type giving
var string : String = "Hello world"
```

* But we can't convert the `String` type to another type
```swift
print("prints the line");
```

* if we want to print the value of the `string`
* we can do that using \()
```swift
print("The string is \(string)")
```

# For explicit specifying of type
* Int or Int64 --> integer type
* UInt64 --> Unsigned 64 bit integer
* Double or Float --> float type
* String --> strings
* Bool --> boolean values

```swift
print("The largest Unsigned integer: \(UInt.max)")
```

* FLT_MAX and DBL_MAX gives the maximux values.
* for floats we have accuracy precision of 6 digits
* for double we have accuracy precision of 15 digits

```swift
let isDead : Bool = true
print(isDead)
```
