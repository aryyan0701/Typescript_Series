# Type Alias in TypeScript - TypeScript Tutorial 12

## TLDR
Type aliases in TypeScript allow us to give a name to a type, making our code more reusable and readable.

## Key Insights
- Using type aliases simplifies code and makes it more readable.
- Type aliases can be used for any type available in TypeScript, not just unions.
- Type aliases can also be used for object types or primitive data types.

## Type Aliases in TypeScript

### Introduction
Type aliases in TypeScript provide a mechanism to assign a name to a type, enhancing code clarity and reusability.

### Example of Reusability
By utilizing type aliases, we can assign a meaningful name, such as 'ID,' to a union type representing both string and number. This practice enhances code reuse and conciseness.

```typescript
type ID = string | number;

// Usage of the 'ID' type alias
const userId: ID = 'user123';
const postId: ID = 456;

type Point = {
  x: number;
  y: number;
};

type RGBColor = 'red' | 'green' | 'blue';

// Usage of type aliases for object types and literal types
const origin: Point = { x: 0, y: 0 };
const primaryColor: RGBColor = 'red';

