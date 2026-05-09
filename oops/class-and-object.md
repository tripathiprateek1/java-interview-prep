# Class and Object in Java

## What is a Class?

A class is a blueprint or template used to create objects.
It defines properties (variables) and behaviors (methods) that an object will have.

### Example

```java
class Car {

    String color;

    void start() {
        System.out.println("Car Started");
    }
}
```

---

## What is an Object?

An object is an instance of a class.It is a real-world entity created from a class.
It occupies memory and can access the properties and methods defined inside the class.

### Example

```java
Car car1 = new Car();
```

---

## Interview Points

- Class is a blueprint
- Object is an instance
- Object occupies memory
- One class can create multiple objects
