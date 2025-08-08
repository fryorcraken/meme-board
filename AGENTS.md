# AGENTS.md - Development Guidelines

## Build/Test Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix linting issues
- `npm run type-check` - Run TypeScript type checking
- `npm test` - Run all tests
- `npm test -- --testNamePattern="test name"` - Run single test by name
- `npm run test:watch` - Run tests in watch mode

## Code Style Guidelines
- Use TypeScript for all new code
- Prefer named exports over default exports
- Use camelCase for variables/functions, PascalCase for components/classes
- Import order: external libraries, internal modules, relative imports
- Use async/await over Promises where possible
- Handle errors with try/catch blocks, avoid silent failures
- Use meaningful variable names, avoid abbreviations
- Keep functions small and focused (single responsibility)
- Use const/let appropriately, avoid var
- Add JSDoc comments for complex functions
- Use strict TypeScript settings, avoid 'any' type