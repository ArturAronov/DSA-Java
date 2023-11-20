# Notes
### Fundamentals: `static` method
- when you declare a variable or a method as `static`, it belongs to the class, rather than a specific instance
- _signature_ = `public static`
- method overloading is a feature of Java in which a class has more than one method of the same name and their parameters are different
- a method can have side-effects by using keyword `void` as its return type
- technically `void` methods are not implemented in mathematical functions

### Fundamentals: `String`
- String is NOT a primitive type
- Java has a built-in _concatenation_ operator ( + ) for `String` like the build-in operators that it has for primitive types
- Conversion:
  - `static int parseInt(String s)`
  - `static String toString(int i)`
  - `static double parseDouble(String s)`
  - `static String toString(double x)`
- We rarely explicitly use the `static toString()` method just described because Java has a built-in mechanism that allows us to convert from any data type value to `String` value by using concatenation: if _one_ of the arguments of + is a `String`, Java _automatically_ converts the other argument to a `String` 