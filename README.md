# Arithmetic Operations

A simple and lightweight arithmetic utility library for JavaScript and TypeScript.

This package provides common arithmetic operations such as addition, subtraction, multiplication, and division, with full TypeScript support.

---

## 📦 Installation

```bash
npm install @adun-upathilak/arithmetic-operations
```

or

```bash
yarn add @adun-upathilak/arithmetic-numbers
```

---

## 🚀 Usage

### Import (recommended: named imports)

```ts
import {
  addNumbers,
  addTwoNumbers,
  subtractNumbers,
  multiplyNumbers,
  divideNumbers,
} from "@adun-upathilak/arithmetic-operations";
```

---

## ➕ addNumbers

Adds multiple numbers together.

```ts
addNumbers(1, 2, 3, 4); // 10
```

---

## ➕ addTwoNumbers

Adds two numbers.

```ts
addTwoNumbers(5, 7); // 12
```

---

## ➖ subtractNumbers

Subtracts the second number from the first.

```ts
subtractNumbers(10, 4); // 6
```

---

## ✖️ multiplyNumbers

Multiplies two numbers.

```ts
multiplyNumbers(3, 4); // 12
```

---

## ➗ divideNumbers

Divides the first number by the second.

⚠️ Throws an error if the divisor is `0`.

```ts
divideNumbers(10, 2); // 5
```

```ts
divideNumbers(10, 0); // ❌ Error: Division by zero is not allowed
```

---

## ⚠️ Error Handling Example

```ts
try {
  divideNumbers(10, 0);
} catch (error) {
  console.error(error.message);
}
```

---

## 📌 Default Export (Not Recommended)

The package also provides a default export as an array of functions:

```ts
import Maths from "@adun-upathilak/arithmetic-operations";

const [
  addNumbers,
  subtractNumbers,
  multiplyNumbers,
  divideNumbers,
  addTwoNumbers,
] = Maths;
```

👉 **Named imports are recommended** for better readability and type safety.

---

## 🛠 Built With

- TypeScript
- semantic-release
- npm

---

## 📄 License

ISC

---

## 👤 Author

**Adun Arosh Upathilak**

---

## ⭐ Contributing

Feel free to open issues or submit pull requests to improve this package.
