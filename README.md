# A config package for TypeScript

## Installation

1. Add `"@simplyundoable/eslint-plugin": "git+https://github.com/simplyundoable/package-typescript.git",` to your package.json devDependencies

## Update this package

1. `make publish`

## Usage

### Tsconfig

```json
{
 "extends": "./node_modules/@simplyundoable/typescript-preset/ts",
 "compilerOptions": {
  "noEmit": false,
  "baseUrl": "./src",
  "paths": {
   "~*": ["./*"]
  },
  "outDir": "build"
  },
 "include": [
    "src"
  ],
  "exclude": [
    "node_modules",
    "build",
    "app"
  ]
}
```
