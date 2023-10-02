# 1. Variables

## 1.1 Variable declaration

This is the most basic way to declare a variable.

```go
var a int = 10
var b, c int = 1, 2
var d = 11
var e int
e = 10
```

## 1.2 Variable initialization

The variable declaration and initialization can be combined in one statement.

```go
var a, b int = 1, 2
var s string = "abc"
var (
    a int
    b bool
)
```

## 1.3 Anonymous variable

Anonymous variables are not declared with the `var` keyword.

```go
a, b := 1, 2
```

## 1.4 Variable scope

Variables can be declared inside functions, and are only accessible within the function.

```go
func main() {
    var a int
    {
        var a int
        fmt.Println(a)
    }
    fmt.Println(a)
}
```

## 1.5 Variable type

Variables have to be declared with a type. Here are some examples:

```go
var name string = "John" // string
var age int = 27 // int is a signed integer, can be positive or negative
var age uint = 27 // uint is an unsigned integer, can only be positive
var isMarried bool = false // boolean can be true or false
var height float32 = 1.78 // float32 is a 32-bit floating point number
var weight float64 = 70.2 // float64 is a 64-bit floating point number
```

## 1.6 Variable type conversion

```go
var a int = 10 // int
var b float32 = float32(a) // float32
var c float64 = float64(a) // float64
var d int = int(b) // int
var e int = int(c) // int
```

## 1.7 Variable type declaration

```go
var (
    a int
    b float32
    c bool
)
```

## 1.8 Variable type declaration and initialization

```go
var a, b int = 1, 2
var s string = "abc"
var (
    a int
    b bool
)
```
