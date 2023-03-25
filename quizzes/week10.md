# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
This is where you can group related types together like classes to avoid naming conflicts with other types
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class can be inherited, and  a struct cannot
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
constructor
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
The functions name
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
what the expected return type to be
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is preventing another class that inherits Car to provide its own implementation for starting the car
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
This marks the method as something that can be overridden by a derived class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, and internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only code within the same class
```