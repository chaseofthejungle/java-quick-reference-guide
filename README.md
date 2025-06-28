# Java Quick Reference Guide
  
**Description/Overview:** A lookup 'sheet' of common use Java methods, boilerplate code, and more. For more advanced data structures guidance/solutions and clean coding advice, see the [Supplemental Resources section](#supplemental).
  
#### Table of Contents

1. [Syntax and Data Types](#syntax)
2. [Mathematical and Logical Operators](#math)
3. [Control Flow/Decision Structures](#control)
4. [Arrays](#arrays)
5. [Strings](#strings)
6. [Methods](#methods)
7. [Object-Oriented Programming (OOP) Principles](#oop)
8. [Exception Handling](#exceptions)
9. [Java Collections Framework (JCF)](#jcf)
10. [Generics](#generics)
11. [File Input/Output (I/O)](#file)
12. [Multithreading](#multithreading)
13. [Lambda Expressions and Functional Interfaces](#lambdas)
14. [Stream API](#streams)
15. [Time API](#time)
16. [Networking](#networking)
17. [Reflection](#reflection)
18. [Annotations](#annotations)
19. [Java Database Connectivity (JDBC)](#jdbc)
20. [Supplemental Resources](#supplemental)
  
<hr />

## 1. <a name="syntax">Syntax and Data Types</a>

(TODO)

<hr />

## 2. <a name="math">Mathematical and Logical Operators</a>

(TODO)

<hr />

## 3. <a name="control">Control Flow/Decision Structures</a>

(TODO)

<hr />

## 4. <a name="arrays">Arrays</a>

(TODO)

<hr />

## 5. <a name="strings">Strings</a>

(TODO)

<hr />

## 6. <a name="methods">Methods</a>
  
* Method declaration: `public int addVals(int a, int b) { return a + b; }`
* Method overload (if added to a class with the above method): `public int addVals(int a, int b, int c) { return a + b + c; }`
    
<hr />

## 7. <a name="oop">Object-Oriented Programming (OOP) Principles</a>

(TODO)

<hr />

## 8. <a name="exceptions">Exception Handling</a>

(TODO)

<hr />

## 9. <a name="jcf">Java Collections Framework (JCF)</a>

(TODO)

<hr />

## 10. <a name="generics">Generics</a>
  
* Generic class: `public class ClassName<T> { }`
* Generic method: `public <T> void methodName(T parameter) { }`
* Bounded type parameter (with generic method): `public <T extends Number> void methodName(T parameter) { }`
* Wildcard: `public void methodName(List<?> list) { }`
  
<hr />

## 11. <a name="file">File Input/Output (I/O)</a>

(TODO)

<hr />

## 12. <a name="multithreading">Multithreading</a>

(TODO)

<hr />

## 13. <a name="lambdas">Lambda Expressions and Functional Interfaces</a>

(TODO)

<hr />

## 14. <a name="streams">Stream API</a>

(TODO)

<hr />

## 15. <a name="time">Time API</a>

<strong>Retrieving present values...</strong>
  
* Present date: `LocalDate date = LocalDate.now();`
* Present time: `LocalTime time = LocalTime.now();`
* Present date and time: `LocalDateTime dateTime = LocalDateTime.now();`
* Present day (of week): `DayOfWeek dayOfWeek = date.getDayOfWeek();`
  
<strong>Retrieving more specific values...</strong>
  
* A specific date: `LocalDate date = LocalDate.of(2024, 10, 6);`
* Period between dates: `Period period = Period.between(date1, date2);`
* Duration between times: `Duration duration = Duration.between(time1, time2);`

<strong>Performing mathematical operations...</strong>

* Adding days to a date: `LocalDate future = date.plusDays(5);`
* Adding years to a date: `LocalDate future = date.plusYears(4);`
* Subtracting months from a date: `LocalDate past = date.minusMonths(2);`

<strong>Parsing, formatting, and conditional logic...</strong>

* Parsing a date (from String data): `LocalDate date = LocalDate.parse("2020-02-09");`
* Formatting a date (from String data): `String formatted = date.format(DateTimeFormatter.ISO_DATE);`
* Evaluate if a year is a leap year: `boolean isLeapYear = date.isLeapYear();`
  
<hr />

## 16. <a name="networking">Networking</a>

(TODO)

<hr />

## 17. <a name="reflection">Reflection</a>

(TODO)

<hr />

## 18. <a name="annotations">Annotations</a>

(TODO)

<hr />

## 19. <a name="jdbc">Java Database Connectivity (JDBC)</a>

(TODO)

<hr />
  
## 20. <a name="supplemental">Supplemental Resources</a>
  
* *[Java Clean Coding Guide](https://github.com/chaseofthejungle/java-clean-coding-guide)*  
* *[Java Data Structure Leetcode Interview Questions](https://github.com/chaseofthejungle/java-data-structure-leetcode-interview-questions)*
* *[Official Java Website](https://www.java.com/en/)*
   
<hr />
