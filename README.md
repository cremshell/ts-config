# @cremshell/tsconfig

This package provides a reusable `tsconfig.json` setup optimized for:

- React
- Vite
- Strict TypeScript settings

## Usage

Install the package:

```bash
npm install -D @cremshell/tsconfig
```

Then in your project's tsconfig.json:

```json
{
  "extends": "@cremshell/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  },
  "include": ["src"]
}
```
