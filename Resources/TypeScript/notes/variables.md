# 1. Variables

Variables are used to store data. In TypeScript, variables are declared using the `let` and `const` keywords. `let` variables can be reassigned, whereas `const` variables cannot.

## 1.1 Variable declaration

```typescript
let name: string; // let variables can be reassigned
const age: number; // const variables cannot be reassigned
```

## 1.2 Assigning a value to a variable

```typescript
let name: string;

name = "John";
```

## 1.3 Using a variable

```typescript
let name: string;

name = "John";

console.log(name);
```

## 1.4 Updating a variable

```typescript
name = "Jane";
```

## 1.5 Deleting a variable

```typescript
delete name;
```

## 1.6 Variable scope

```typescript
if (true) {
  let name: string;
}

console.log(name);
```

## 1.7 Variable hoisting

```typescript
console.log(name);
let name: string;
```

## 1.8 Variable initialization

```typescript
let name: string = "John";
```

## 1.9 Variable initialization with a function

```typescript
let name: string = () => "John";
```

## 1.10 Variable initialization with a function and parameters

```typescript
let name: string = (firstName: string, lastName: string) =>
  firstName + " " + lastName;
```
