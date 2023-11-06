


# TypeScript Data Types

TypeScript, being a statically-typed superset of JavaScript, offers a variety of data types to define the shape and characteristics of variables. Here, we'll cover the fundamental concepts of data types in TypeScript.

## Basic Data Types

### Primitive Data Types

- **Number**: Represents numeric values, including integers and floating-point numbers.
- **String**: Represents text or character data enclosed in single or double quotes.
- **Boolean**: Represents a binary value, either `true` or `false`.
- **Null**: Represents the intentional absence of any object value.
- **Undefined**: Represents a variable that has been declared but not assigned any value.
- **Symbol**: Represents unique and immutable values used primarily as object property keys.

### Non-Primitive Data Types

- **Object**: Represents complex data structures, including custom objects and arrays.
- **Array**: A special object type used for storing collections of data.
- **Function**: Represents a callable object, which can have parameters and a return type.
- **Tuple**: An array with a fixed number of elements, where each element may have a different data type.
- **Enum**: A user-defined data type with a set of named values.
- **Any**: A dynamic type that can hold values of any data type. Avoid using `any` for type safety.

## Inferred and Explicit Data Types

In TypeScript, data types can be inferred or specified explicitly. When you declare a variable without specifying its type, TypeScript infers the type based on the assigned value. Explicit typing allows you to specify the data type of a variable.

### Inferred Data Types

```typescript
let x = 5; // TypeScript infers x as a number.
let message = "Hello, TypeScript!"; // TypeScript infers message as a string.
```

### Explicit Data Types

```typescript
let count: number = 10; // Explicitly specify count as a number.
let greeting: string = "Welcome to TypeScript!"; // Explicitly specify greeting as a string.
```

## Exclusive Data Types

TypeScript introduces custom types to improve code clarity and safety. You can create custom data types using `type` and `interface`.

- **Type**: Defines a custom data type that can represent a union, intersection, or specific data structure.
- **Interface**: Defines a contract for object shapes, ensuring that objects of that type conform to a specific structure.

```typescript
type User = { name: string, age: number };
interface Car {
  brand: string;
  model: string;
}
```
 For more detailed information, consult the official TypeScript documentation: [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html).

