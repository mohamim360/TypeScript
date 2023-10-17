# Compiling TypeScript to JavaScript and the Difference in Two Files

This code demonstrates a simple web application that allows users to input two numbers and add them together when clicking a button. It is implemented in both plain JavaScript and TypeScript, highlighting how TypeScript code is compiled to JavaScript and the differences between the two files.

## Understanding TypeScript and JavaScript:

### HTML File (index.html):

- The HTML file defines the structure of the web page.
- It includes a script tag with the "using-ts.js" file, which is the compiled JavaScript code from TypeScript.

### JavaScript File (using-ts.js):

- This file contains the JavaScript code equivalent to the TypeScript code.
- The variables, functions, and event listeners are written using standard JavaScript.

### TypeScript File (using-ts.ts):

- This file contains the TypeScript code.
- It is essentially JavaScript with type annotations, providing stronger type checking and better tooling support.

## Key Differences Between the Two Files:

### Type Annotations:

- In the TypeScript file, you will notice type annotations, such as `num1: number` in the function parameter list. These annotations specify the expected types of variables and function parameters, enhancing type safety and code clarity.

### Strict Null Checks:

- TypeScript enforces strict null checks by default. In the TypeScript code, you can see "!" used after element selections like `document.querySelector("button")!`. This tells TypeScript that the elements will not be null, allowing it to compile successfully.

### Compile Process:

- TypeScript needs to be transpiled into JavaScript to run in a browser. This is done using the TypeScript compiler (tsc). The "using-ts.js" file is the result of compiling "using-ts.ts." The TypeScript code is converted into JavaScript code that browsers can understand.

## How to Compile TypeScript to JavaScript:

1. Install TypeScript globally (if not already installed): `npm install -g typescript`

2. Compile the TypeScript code:
   - Open a terminal in the project directory.
   - Run the TypeScript compiler: `tsc using-ts.ts`

   This will generate a JavaScript file (using-ts.js) from the TypeScript code.

3. Open the HTML file (index.html) in a web browser. The JavaScript code, after compilation, will execute and provide the same functionality as the TypeScript code.

By comparing these two files, you can see the additional benefits TypeScript brings in terms of type safety and code documentation. TypeScript helps catch errors during development and enhances code maintainability, making it a valuable choice for larger and more complex projects.
