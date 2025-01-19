# Implicit Type Coercion in TypeScript

This repository demonstrates a common error in TypeScript where implicit type coercion can lead to runtime errors that are not caught during compilation.

The `bug.ts` file contains code that adds a number and a string.  While TypeScript allows this, it results in a runtime error because of the implicit type coercion performed by JavaScript.

The `bugSolution.ts` file shows how to prevent this error by using explicit type checking or type guards.