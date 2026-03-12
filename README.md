# Node TypeScript Template

Minimal **Node.js + TypeScript** template for quickly starting new backend or CLI projects.

This repository is configured as a template so new projects can be created directly from it without repeating the basic setup.

## Features

* Modern **ES Modules**
* **TypeScript** configuration ready to use
* Fast development with **tsx**
* Clean project structure
* Path alias support (`#app/*`)
* Separate `src` and `build` directories

## Project Structure

```
.
├─ build/
├─ node_modules/
├─ src/
│  └─ index.ts
├─ .gitignore
├─ package.json
└─ tsconfig.json
```

## Getting Started

Create a new repository using this template on GitHub or clone it manually.

### Install dependencies

```
npm install

```

### Development mode

Runs the project with hot reload using `tsx`.

```
npm run dev

```

### Build

Compiles TypeScript into the `build` directory.

```
npm run build

```

### Run production build

```
npm start

```

## Path Aliases

The project includes a path alias:

```
#app/*

```

Example:

```ts
import { something } from "#app/utils/example.js";

```

Configured in:

* `tsconfig.json`
* `package.json`

## Requirements

* Node.js 18+

## License

MIT
