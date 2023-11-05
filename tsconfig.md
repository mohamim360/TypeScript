


# TypeScript Configuration (tsconfig.json)

Below is a sample `tsconfig.json` file, which is used to configure TypeScript settings for your project.

```json
{
  "compilerOptions": {
    "target": "es2016",
    "rootDir": "./",
    "outDir": "./dist/"
  }
}
```

## Configuration Options

- **target**: This option specifies the ECMAScript target version that TypeScript will compile your code to. In this example, it's set to "es2016," which corresponds to ECMAScript 2016 (ES7). You can change this to match the ECMAScript version you need for your project.

- **rootDir**: The `rootDir` option specifies the root directory of your TypeScript source code. This is where TypeScript will look for your `.ts` files. In this example, it's set to the project's root directory.

- **outDir**: The `outDir` option determines the output directory for the compiled JavaScript files (`.js`). In this example, it's set to a directory named "dist" in the project's root.

You can customize these options according to your project's requirements.

For more information on configuring TypeScript, please refer to the [official TypeScript documentation](https://www.typescriptlang.org/tsconfig).
