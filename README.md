# Interview Question :

## \*\*\* What are some differences between interfaces and types in TypeScript?

### interface:

- To use interfaces, we need to start with the interface

#### Examples

```javascript
interface User2 {
  name: string;
}
```

- interface like Object
- interface use in array, Object function, Object.
- We need increase our property use intersectoin.

#### Examples

```javascript
  interface userIncrease = user1 & { role: string };
```

### types:

- To use type, we need to start with the type

#### Examples

```javascript
  interface User2 = { name: string };
```

- Type aliases can be used to represent primitive types if we want.
- type after extends possible make interface.
- If need increase property use extends

#### Examples

```javascript
interface userIncrease extends user1 {
  name: string;
}
```

## \*\*\* What is type inference in TypeScript? Why is it helpful?

TypeScript type interface is a powerfull feature that makes your code clean and safe.

- Variable Declarations

```javascript
let username = "John";
```

- Function Return

```javascript
function getAge() {
  return 30;
}
```

- Function Parameter

```javascript
function greet(message = "Hello") {
  console.log(message);
}
```

- Array Interface

```javascript
let number = [1, 2, 3];
let string = ["A", "B", "C"];
```

- Object Interface

```javascript
let user = { name: "sohel", age: 25 };
```

- Destructuring interface

```javascript
const { name, age } = user;
```

## \*\*\* How does TypeScript help in improving code quality and project maintainability?

TypeScript is an Object Oriented Programming Language that is built on top of JS with Extra Features. TypeScript develop with javascript lot of improve Features. When working in large Application with Multiple Developers TypeScript give us instant error soluation, maintainability. TyteScript code can be transpiled into older versions of javascript like ES3, ES5, ES6.

- Early Error Detection
- Self-Documenting code
- Safer Refactoring
- Editor Enhancemnts facilities
- Emforced Architectural Boundaries
- Improved Collaboration
- Gradual Adoption & Incremental Safety
- Rich Type System for complex Domains
- Reduced Runtime Bugs
- Long-Term maintainability
