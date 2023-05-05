# Ada Cheat Sheet for Python and C++ Programmers

Ada is a strongly-typed, statically-typed, and high-level programming language that is designed for critical software systems. The following cheat sheet provides an overview of Ada's basic features and syntax, along with equivalent Python and C++ code for comparison. Keep in mind that Ada is more verbose than Python and C++, which may result in longer code snippets.

## 1. Variables and Types

| Description | Ada                           | Python               | C++                       |
|-------------|-------------------------------|----------------------|---------------------------|
| Integer     | `I : Integer := 42;`          | `i = 42`             | `int i = 42;`             |
| Float       | `F : Float := 3.14;`          | `f = 3.14`           | `float f = 3.14;`         |
| Boolean     | `B : Boolean := True;`        | `b = True`           | `bool b = true;`          |
| Character   | `C : Character := 'A';`       | `c = 'A'`            | `char c = 'A';`           |
| String      | `S : String := "Hello, World!";` | `s = "Hello, World!"` | `std::string s = "Hello, World!";` |

### Array

Ada:

```Ada
type Integer_Array is array(1 .. 5) of Integer;
A : Integer_Array := (1, 2, 3, 4, 5);
```

Python:

```Python
a = [1, 2, 3, 4, 5]
```

C++:

```cpp
int a[] = {1, 2, 3, 4, 5};
```

## 2. Control Structures

### If statement

Ada:

```Ada
if B then
   -- Code
elsif Other_Condition then
   -- Code
else
   -- Code
end if;
```

Python:

```Python
if b:
   # Code
elif other_condition:
   # Code
else:
   # Code
```

C++:

```cpp
if (b) {
   // Code
} else if (other_condition) {
   // Code
} else {
   // Code
}
```

### Loops

#### For loop

Ada:

```Ada
for I in 1 .. 10 loop
   -- Code
end loop;
```

Python:

```Python
for i in range(1, 11):
   # Code
```

C++:

```cpp
for (int i = 1; i <= 10; ++i) {
   // Code
}
```

#### While loop

Ada:

```Ada
while Condition loop
   -- Code
end loop;
```

Python:

```Python
while condition:
   # Code
```

C++:

```cpp
while (condition) {
   // Code
}
```

## 3. Functions and Procedures

### Functions

Ada:

```Ada
function Add(X, Y : Integer) return Integer is
begin
   return X + Y;
end Add;
```

Python:

```Python
def add(x, y):
   return x + y
```

C++:

```cpp
int add(int x, int y) {
   return x + y;
}
```

### Procedures

Ada:

```Ada
procedure Display_Message(Msg : String) is
begin
   Put_Line(Msg);
end Display_Message;
```

Python:

```Python
def display_message(msg):
   print(msg)
```

C
