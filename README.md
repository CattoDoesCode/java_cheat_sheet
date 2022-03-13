# java_cheat_sheet

Java Programming Language Cheat Sheet by :smile_cat:CattoDoesCode

### Table of Contents

* [Comments](#Comments)
* [Syntax](#Syntax)
* [Variables](#Variables)
* [References](#References)

## Syntax

#### Main.java

```java
public class Main {

    public static void main(String[] args) {
	    // write your code here
    }
}
```

## Comments

#### Single-line Comment

```java
// This is a sample comment.
```

#### Multi-line Comment

```java
/* This is a sample
multi-line comment. */
```

## Variables

#### Primitive Data Types

| Data Type | Size   | Description                     | Range                                                                                                             |
|-----------|--------|---------------------------------|-------------------------------------------------------------------------------------------------------------------|
| `byte`    | 8-bit  | signed two's complement integer | `-128` to `127 `                                                                                                  |
| `short`   | 16-bit | signed two's complement integer | `-32,768` to `32,767`                                                                                             |
| `int`     | 32-bit | signed two's complement integer | -231 to  231-1 (i.e.,  `-2147483648` to `2147483647`)                                                             |
| `long `   | 64-bit | two's complement                | -263 to  263-1 (i.e.,  `-9223372036854775808` to `9223372036854775807                                             |
| `float`   | 32-bit | IEEE 754 floating point         | Negative range: `-3.4028235E+38` to `-1.4E-45` Positive range: `1.4E-45` to `3.4028235E+38`                       |
| `double`  | 64-bit | IEEE 754 floating point         | Negative range: `-1.7976931348623157E+308` to `-4.9E-324` Positive range: `4.9E-324` to `1.7976931348623157E+308` |
| `boolean` | 1-bit  | has only two possible values    | `true` or `false`                                                                                                 |
| `char`    | 16-bit | single 16-bit Unicode character | `'\u0000'` (or 0) to `'\uffff'` (or 65,535 inclusive)                                                             |

> `String` in Java is not a primitive data type but an object that are backed by char array. 

#### Declaring a Variable syntax:

```
<DataType> <variableName>;
```

_sample code:_

```java
int numVariable; // variable name is in camelCase
char my_variable; // variable name is in snake_case
```

#### Default Values

| Data Type               | Default Value |
|-------------------------|---------------|
| `byte`                  | 0             |
| `short `                | 0             |
| `int`                   | 0             | 
| `long`                  | 0L            | 
| `float`                 | 0.0f          |
| `double`                | 0.0d          |
| `char`                  | '\u0000'      |
| `boolean`               | false         |
| `String`(or any object) | null          |

#### Assigning a Variable a value:

```
<variableName> = <value or expression>;
```

_sample code:_

```java
numVariable = 100; 
my_variable = 'x'; // single quotation marks ('') for char and double quotation marks for string("")
```

<br/><br/>

### References

* Java Documentation | [docs.oracle.com](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html "Java Documentation")
* [mathcenter.oxford.emory.edu](http://mathcenter.oxford.emory.edu/site/cs170/variables/#:~:text=There%20are%208%20primitive%20types,double%2C%20boolean%2C%20and%20char. "Variables and the 8 Primitive Data Types")
* [w3schools.com](https://www.w3schools.com/java/default.asp "Java Tutorial")
* [javatpoint.com](https://www.javatpoint.com/java-tutorial "Java Tutorial")
* [geeksforgeeks.org](https://www.geeksforgeeks.org/strings-in-java/#:~:text=Strings%20in%20Java%20are%20Objects,entirely%20new%20String%20is%20created.)

