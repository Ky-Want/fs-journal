# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace keyword is used to declare a scope that contains a set of related objects. You can use a namespace to organize code elements and to create globally unique types.
```

**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types while classes are reference types. Structs can be instantiated without using a new operator. A struct cannot inherit from another struct or class, and it cannot be the base of a class. All structs inherit directly from System.ValueType, which inherits from System.Object. Struct cannot be a base class.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
<!-- FIXME later -->
```
Example class contains setdata () method which is used to set the value of str, and Display () method is used to display the value of str, and Astr () is used to add the value of passed object in current object and adding the sum in another object. In Main method, three objects o1, o2, and o3 of Example class are created.
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
<!-- FIXME later -->
```
The abstract classes are used to achieve abstraction in C#. Abstraction is one of the important concepts of object-oriented programming. It allows us to hide unnecessary details and only show the needed information. This helps us to manage complexity by hiding details with a simpler, higher-level idea.
```

**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
A string is a data type used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers. It is comprised of a set of characters that can also contain spaces and numbers. For example, the word "hamburger" and the phrase "I ate 3 hamburgers" are both strings.
```

**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The abstract modifier indicates that the thing being modified has a missing or incomplete implementation. The abstract modifier can be used with classes, methods, properties, indexers, and events.
```

**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class. For example, this method can be overridden by any class that inherits it: C# Copy public virtual double Area() { return x * y; }
```

**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Class, record, and struct accessibility Class, record, and struct member accessibility Other types C# language specification See also All types and type members have an accessibility level. The accessibility level controls whether they can be used from other code in your assembly or other assemblies.
```

**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
A Keyword private is a type of access modifier used to compile-time error when accessed outside the class or member used. It is ideally used to hide the function and variables from other member classes, but the same class's function can access the private member in it.
```