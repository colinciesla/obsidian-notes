# C-Sharp Notes
- [[#1. Variables|1. Variables]]
	- [[#1. Variables#`string`|`string`]]
	- [[#1. Variables#`int`|`int`]]
	- [[#1. Variables#`double`|`double`]]
	- [[#1. Variables#`decimal`|`decimal`]]
	- [[#1. Variables#`bool`|`bool`]]
	- [[#1. Variables#`null`|`null`]]
	- [[#1. Variables#`DateTime`|`DateTime`]]
	- [[#1. Variables#`DateOnly`|`DateOnly`]]
	- [[#1. Variables#`TimeOnly`|`TimeOnly`]]
	- [[#1. Variables#Type Conversions|Type Conversions]]
- [[#2. Conditionals|2. Conditionals]]
	- [[#2. Conditionals#`if` Statements|`if` Statements]]
	- [[#2. Conditionals#`switch` Statements|`switch` Statements]]
- [[#3. Loops and Sets|3. Loops and Sets]]
	- [[#3. Loops and Sets#`do`/`while`|`do`/`while`]]
	- [[#3. Loops and Sets#Arrays|Arrays]]
	- [[#3. Loops and Sets#Lists|Lists]]
	- [[#3. Loops and Sets#Dictionary|Dictionary]]
	- [[#3. Loops and Sets#`for`|`for`]]
	- [[#3. Loops and Sets#`foreach`|`foreach`]]
- [[#4. Methods|4. Methods]]
	- [[#4. Methods#Creating a Method|Creating a Method]]
	- [[#4. Methods#Calling a Method|Calling a Method]]
	- [[#4. Methods#Design Principles|Design Principles]]
	- [[#4. Methods#Method Parameters|Method Parameters]]
	- [[#4. Methods#Returning Data|Returning Data]]
	- [[#4. Methods#Tuples|Tuples]]
- [[#5. Debugging|5. Debugging]]
	- [[#5. Debugging#Breakpoints|Breakpoints]]
	- [[#5. Debugging#Exceptions|Exceptions]]
	- [[#5. Debugging#Advanced Exceptions|Advanced Exceptions]]
	- [[#5. Debugging#Advanced Breakpoints|Advanced Breakpoints]]
- [[#6. Classes|6. Classes]]
	- [[#6. Classes#Static Classes|Static Classes]]
	- [[#6. Classes#Instantiated Classes|Instantiated Classes]]
	- [[#6. Classes#Property Types|Property Types]]
	- [[#6. Classes#Namespaces|Namespaces]]
	- [[#6. Classes#Class Libraries|Class Libraries]]
- [[#7. Interfaces and Inheritance|7. Interfaces and Inheritance]]
	- [[#7. Interfaces and Inheritance#Inheritance|Inheritance]]
	- [[#7. Interfaces and Inheritance#Interfaces|Interfaces]]
- [[#8. Modifiers, Abstract, and Overrides|8. Modifiers, Abstract, and Overrides]]
	- [[#8. Modifiers, Abstract, and Overrides#Access Modifiers|Access Modifiers]]
	- [[#8. Modifiers, Abstract, and Overrides#Abstract Classes|Abstract Classes]]
	- [[#8. Modifiers, Abstract, and Overrides#Method Overriding|Method Overriding]]
- [[#9. Overloads and Extensions|9. Overloads and Extensions]]
	- [[#9. Overloads and Extensions#Method Overloading|Method Overloading]]
	- [[#9. Overloads and Extensions#Extension Methods|Extension Methods]]
- [[#10. Generics and Events|10. Generics and Events]]
	- [[#10. Generics and Events#Generics|Generics]]
	- [[#10. Generics and Events#Events|Events]]
- [[#11. Introduction to .NET Core|11. Introduction to .NET Core]]
- [[#12. Class Libraries|12. Class Libraries]]
- [[#13. Unit Tests|13. Unit Tests]]
- [[#14. WinForms|14. WinForms]]
- [[#15. WPF Core|15. WPF Core]]
- [[#16. ASP.NET Core Razor Pages|16. ASP.NET Core Razor Pages]]
- [[#17. ASP.NET Core MVC|17. ASP.NET Core MVC]]
- [[#18. ASP.NET Core API|18. ASP.NET Core API]]
- [[#19. Blazor Server|19. Blazor Server]]
- [[#20. Blazor WebAssembly|20. Blazor WebAssembly]]
- [[#21. SQL Types|21. SQL Types]]
	- [[#21. SQL Types#Basic Normalization|Basic Normalization]]
	- [[#21. SQL Types#ORM|ORM]]
	- [[#21. SQL Types#SQL Server|SQL Server]]
	- [[#21. SQL Types#SQLite|SQLite]]
	- [[#21. SQL Types#MySQL|MySQL]]
- [[#22. NoSQL Types|22. NoSQL Types]]
	- [[#22. NoSQL Types#Concepts|Concepts]]
	- [[#22. NoSQL Types#MongoDB|MongoDB]]
	- [[#22. NoSQL Types#CosmosDB|CosmosDB]]
- [[#23. Other Data Access Types|23. Other Data Access Types]]
- [[#24. Text Files|24. Text Files]]
- [[#25. APIs|25. APIs]]
- [[#26. Other Access Methods|26. Other Access Methods]]
- [[#27. Linq/Lambdas|27. Linq/Lambdas]]
- [[#28. Entity Framework Core|28. Entity Framework Core]]

## 1. Variables

### `string`
- Empty string can be initialized using `""` or `string.Empty`
- String Interpolation: `$"{myVariable}"`
- String manipulation creates a copy in memory each time
- `\` is the *escape character*
- `@` is the *string literal*. Prefix a string with `@` and all characters are treated as regular characters
- Can mix escape character and string literal using `$@`

### `int`
- Initial value is `0`
- `int` or explicitly a signed `Int32` can range from `-2,147,483,648` to` 2,147,483,647`
- Unsigned integer or `UInt32` ranges from `0` to `4,294,967,295`
- Decimals values are truncated

### `double`
- Can have a decimal point
- When writing arithmetic operations, whole numbers are **explicitly integers**, so only using whole numbers will return an `int`. To return a `double`, include a decimal in any number in the operation

### `decimal`

### `bool`

### `null`

### `DateTime`

### `DateOnly`

### `TimeOnly`

### Type Conversions

## 2. Conditionals

### `if` Statements

### `switch` Statements

## 3. Loops and Sets

### `do`/`while`

### Arrays

### Lists

### Dictionary

### `for`

### `foreach`

## 4. Methods

### Creating a Method

### Calling a Method

### Design Principles

### Method Parameters

### Returning Data

### Tuples

## 5. Debugging

### Breakpoints

### Exceptions

### Advanced Exceptions

### Advanced Breakpoints

## 6. Classes

### Static Classes

### Instantiated Classes

### Property Types

### Namespaces

### Class Libraries

## 7. Interfaces and Inheritance

### Inheritance

### Interfaces

## 8. Modifiers, Abstract, and Overrides

### Access Modifiers

### Abstract Classes

### Method Overriding

## 9. Overloads and Extensions

### Method Overloading

### Extension Methods

## 10. Generics and Events

### Generics

### Events

## 11. Introduction to .NET Core

## 12. Class Libraries

## 13. Unit Tests

## 14. WinForms

## 15. WPF Core

## 16. ASP.NET Core Razor Pages

## 17. ASP.NET Core MVC

## 18. ASP.NET Core API

## 19. Blazor Server

## 20. Blazor WebAssembly

## 21. SQL Types

### Basic Normalization

### ORM

### SQL Server

### SQLite

### MySQL

## 22. NoSQL Types

### Concepts

### MongoDB

### CosmosDB

## 23. Other Data Access Types

## 24. Text Files

## 25. APIs

## 26. Other Access Methods

## 27. Linq/Lambdas

## 28. Entity Framework Core

