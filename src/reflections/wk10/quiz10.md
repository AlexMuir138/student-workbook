# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To assign an attribute to a file that can be called by others.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class is a reference type whereas struct is a vaalue type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
constructors
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
return type will be a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it is preventing instantiation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
To allow the base class to be modified within the function
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, and internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only by the writer of the code
```