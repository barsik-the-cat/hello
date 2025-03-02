### **1. Python**
```python
print("Hello, World!")
```

---

### **2. JavaScript**
```javascript
console.log("Hello, World!");
```

---

### **3. Java**
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

### **4. C**
```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

---

### **5. C++**
```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

---

### **6. C#**
```csharp
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```

---

### **7. PowerShell**
```powershell
Write-Host "Hello, World!"
```

---

### **8. Bash**
```bash
echo "Hello, World!"
```

---

### **9. Lua**
```lua
print("Hello, World!")
```

---

### **10. Go**
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

---

### **11. Ruby**
```ruby
puts "Hello, World!"
```

---

### **12. PHP**
```php
<?php
echo "Hello, World!";
?>
```

---

### **13. Rust**
```rust
fn main() {
    println!("Hello, World!");
}
```

---

### **14. Swift**
```swift
print("Hello, World!")
```

---

### **15. Kotlin**
```kotlin
fun main() {
    println("Hello, World!")
}
```

---

### **16. TypeScript**
```typescript
console.log("Hello, World!");
```

---

### **17. R**
```r
print("Hello, World!")
```

---

### **18. Perl**
```perl
print "Hello, World!\n";
```

---

### **19. Haskell**
```haskell
main = putStrLn "Hello, World!"
```

---

### **20. Dart**
```dart
void main() {
  print('Hello, World!');
}
```

---

### **21. Elixir**
```elixir
IO.puts("Hello, World!")
```

---

### **22. Scala**
```scala
object Main extends App {
  println("Hello, World!")
}
```

---

### **23. F#**
```fsharp
printfn "Hello, World!"
```

---

### **24. Clojure**
```clojure
(println "Hello, World!")
```

---

### **25. Erlang**
```erlang
-module(hello).
-export([start/0]).

start() ->
    io:fwrite("Hello, World!\n").
```

---

### **26. Prolog**
```prolog
:- write('Hello, World!'), nl.
```

---

### **27. Assembly (x86, Linux)**
```asm
section .data
    msg db 'Hello, World!', 0xA
    len equ $ - msg

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, len
    int 0x80

    mov eax, 1
    int 0x80
```

---

### **28. SQL**
```sql
SELECT 'Hello, World!';
```

---

### **29. HTML + JavaScript**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <script>
        document.write("Hello, World!");
    </script>
</body>
</html>
```

---

### **30. MATLAB**
```matlab
disp('Hello, World!');
```

---

### **31. Fortran**
```fortran
program hello
    print *, "Hello, World!"
end program hello
```

---

### **32. COBOL**
```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
    DISPLAY 'Hello, World!'.
    STOP RUN.
```

---

### **33. Pascal**
```pascal
program HelloWorld;
begin
  WriteLn('Hello, World!');
end.
```

---

### **34. BASIC**
```basic
10 PRINT "Hello, World!"
```

---

### **35. Scheme**
```scheme
(display "Hello, World!")
(newline)
```

---

### **36. Shell (sh)**
```sh
echo "Hello, World!"
```

---

### **37. VBScript**
```vbscript
MsgBox "Hello, World!"
```

---

### **38. Batch (Windows)**
```batch
@echo off
echo Hello, World!
```

---

### **39. PowerShell**
```powershell
Write-Host "Hello, World!"
```

---

### **40. Dart**
```dart
void main() {
  print('Hello, World!');
}
```

---

### **41. Julia**
```julia
println("Hello, World!")
```

---

### **42. Nim**
```nim
echo "Hello, World!"
```

---

### **43. Crystal**
```crystal
puts "Hello, World!"
```

---

### **44. Zig**
```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```

---

### **45. Kotlin (Script)**
```kotlin
println("Hello, World!")
```

---

### **46. Elixir**
```elixir
IO.puts("Hello, World!")
```

---

### **47. Racket**
```racket
#lang racket
(displayln "Hello, World!")
```

---

### **48. OCaml**
```ocaml
print_endline "Hello, World!"
```

---

### **49. F# (Script)**
```fsharp
printfn "Hello, World!"
```

---

### **50. Clojure (Script)**
```clojure
(println "Hello, World!")
```

---

### **51. Erlang (Script)**
```erlang
io:format("Hello, World!~n").
```

---

### **52. Prolog (Script)**
```prolog
:- write('Hello, World!'), nl.
```

---

### **53. Assembly (ARM, Linux)**
```asm
.global _start

_start:
    mov r0, #1
    ldr r1, =message
    ldr r2, =len
    mov r7, #4
    swi 0

    mov r7, #1
    swi 0

message:
    .asciz "Hello, World!\n"
len = . - message
```

---

### **54. SQL (MySQL)**
```sql
SELECT 'Hello, World!';
```

---

### **55. HTML + JavaScript (ES6)**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <script>
        console.log("Hello, World!");
    </script>
</body>
</html>
```

---

### **56. MATLAB (Script)**
```matlab
disp('Hello, World!');
```

---

### **57. Fortran (Modern)**
```fortran
program hello
    print *, "Hello, World!"
end program hello
```

---

### **58. COBOL (Modern)**
```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
    DISPLAY 'Hello, World!'.
    STOP RUN.
```

---

### **59. Pascal (Modern)**
```pascal
program HelloWorld;
begin
  WriteLn('Hello, World!');
end.
```

---

### **60. BASIC (Modern)**
```basic
10 PRINT "Hello, World!"
```

---

### **61. Scheme (Modern)**
```scheme
(display "Hello, World!")
(newline)
```

---

### **62. Shell (Modern)**
```sh
echo "Hello, World!"
```

---

### **63. VBScript (Modern)**
```vbscript
MsgBox "Hello, World!"
```

---

### **64. Batch (Modern)**
```batch
@echo off
echo Hello, World!
```

---

### **65. PowerShell (Modern)**
```powershell
Write-Host "Hello, World!"
```

---

### **66. Dart (Modern)**
```dart
void main() {
  print('Hello, World!');
}
```

---

### **67. Julia (Modern)**
```julia
println("Hello, World!")
```

---

### **68. Nim (Modern)**
```nim
echo "Hello, World!"
```

---

### **69. Crystal (Modern)**
```crystal
puts "Hello, World!"
```

---

### **70. Zig (Modern)**
```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```

---

### **71. Kotlin (Script, Modern)**
```kotlin
println("Hello, World!")
```

---

### **72. Elixir (Modern)**
```elixir
IO.puts("Hello, World!")
```

---

### **73. Racket (Modern)**
```racket
#lang racket
(displayln "Hello, World!")
```

---

### **74. OCaml (Modern)**
```ocaml
print_endline "Hello, World!"
```

---

### **75. F# (Script, Modern)**
```fsharp
printfn "Hello, World!"
```

---

### **76. Clojure (Script, Modern)**
```clojure
(println "Hello, World!")
```

---

### **77. Erlang (Script, Modern)**
```erlang
io:format("Hello, World!~n").
```

---

### **78. Prolog (Script, Modern)**
```prolog
:- write('Hello, World!'), nl.
```

---

### **79. Assembly (ARM, Linux, Modern)**
```asm
.global _start

_start:
    mov r0, #1
    ldr r1, =message
    ldr r2, =len
    mov r7, #4
    swi 0

    mov r7, #1
    swi 0

message:
    .asciz "Hello, World!\n"
len = . - message
```

---

### **80. SQL (MySQL, Modern)**
```sql
SELECT 'Hello, World!';
```

---

### **81. HTML + JavaScript (ES6, Modern)**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <script>
        console.log("Hello, World!");
    </script>
</body>
</html>
```

---

### **82. MATLAB (Script, Modern)**
```matlab
disp('Hello, World!');
```

---

### **83. Fortran (Modern, Modern)**
```fortran
program hello
    print *, "Hello, World!"
end program hello
```

---

### **84. COBOL (Modern, Modern)**
```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
    DISPLAY 'Hello, World!'.
    STOP RUN.
```

---

### **85. Pascal (Modern, Modern)**
```pascal
program HelloWorld;
begin
  WriteLn('Hello, World!');
end.
```

---

### **86. BASIC (Modern, Modern)**
```basic
10 PRINT "Hello, World!"
```

---

### **87. Scheme (Modern, Modern)**
```scheme
(display "Hello, World!")
(newline)
```

---

### **88. Shell (Modern, Modern)**
```sh
echo "Hello, World!"
```

---

### **89. VBScript (Modern, Modern)**
```vbscript
MsgBox "Hello, World!"
```

---

### **90. Batch (Modern, Modern)**
```batch
@echo off
echo Hello, World!
```

---

### **91. PowerShell (Modern, Modern)**
```powershell
Write-Host "Hello, World!"
```

---

### **92. Dart (Modern, Modern)**
```dart
void main() {
  print('Hello, World!');
}
```

---

### **93. Julia (Modern, Modern)**
```julia
println("Hello, World!")
```

---

### **94. Nim (Modern, Modern)**
```nim
echo "Hello, World!"
```

---

### **95. Crystal (Modern, Modern)**
```crystal
puts "Hello, World!"
```

---

### **96. Zig (Modern, Modern)**
```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```

---

### **97. Kotlin (Script, Modern, Modern)**
```kotlin
println("Hello, World!")
```

---

### **98. Elixir (Modern, Modern)**
```elixir
IO.puts("Hello, World!")
```

---

### **99. Racket (Modern, Modern)**
```racket
#lang racket
(displayln "Hello, World!")
```

---

### **100. OCaml (Modern, Modern)**
```ocaml
print_endline "Hello, World!"
```
