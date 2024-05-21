# Express TypeScript Mongoose Starter Pack

A starter template for building Express applications with TypeScript and Mongoose. This template will help you get started quickly with new projects and ensure a consistent setup across your work.

## Features

- **Express.js** for building robust APIs
- **TypeScript** for static type checking
- **Mongoose** for MongoDB object modeling
- **ESLint** for code linting
- **Prettier** for code formatting
- **dotenv** for environment variable management
- **ts-node-dev** for seamless development experience

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Tanzeebul-Tamim/Express-Mongoose-TS-Starter_Pack
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the root directory and copy the contents of `.env.example` into it. Update the values as needed.

   ```bash
   cp .env.example .env
   ```

## Development

Start the development server:

```bash
npm run dev
```

## Build

Compile the TypeScript code:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

## Lint

Run ESLint to check for code issues:

```bash
npm run lint
```

Automatically fix linting issues:

```bash
npm run lint:fix
```

## Format

Format your code using Prettier:

```bash
npm run format
```

## Project Structure

```
src
  ├── app
      ├── config
          ├── index.ts    # Load environment variables using dotenv from the .env file and export them as configuration options
  ├── app.ts              # Express app setup
  ├── server.ts           # Entry point
.env.example              # Example environment variables
.eslintignore             # Specifies files and directories to ignore during ESLint linting
.eslintrc.json            # ESLint configuration
.gitignore                # Specifies files and directories to ignore in Git version control
.prettierrc.json          # Prettier configuration
package-lock.json         # Records the exact dependency tree generated by npm for a project
package.json              # NPM scripts, dependencies and dev-dependencies
tsconfig.json             # TypeScript configuration
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.
