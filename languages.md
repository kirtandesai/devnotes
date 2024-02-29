## Best Practices and "Rule of Thumb" for Development

### Python
- **Naming Conventions**:
  - Variables and functions: `snake_case` (`variable_name`)
  - Classes: `PascalCase` (`ClassName`)
  - Constants: `UPPERCASE` (`CONSTANT_VALUE`)
- **Imports**: Group imports in the order of standard library, third-party, and then local imports, each group separated by a blank line.
- **PEP 8**: Follow the [PEP 8 style guide](https://www.python.org/dev/peps/pep-0008/) for coding conventions.

### Go (Golang)
- **Naming Conventions**:
  - Variables and functions: `camelCase` for internal, `PascalCase` for exported names (`variableName`, `FunctionName`)
  - Acronyms capitalized (`HTTPServer`, `URLParser`)
- **Formatting**: Use `gofmt` to automatically format your code.
- **Error Handling**: Prefer explicit error handling over exceptions.
- **Concurrency**: Use Goroutines and channels for concurrent tasks.

### React (JavaScript/TypeScript library for building UIs)
- **Naming Conventions**:
  - Components: `PascalCase` (`MyComponent`)
  - Instances and functions: `camelCase` (`myInstance`, `myFunction`)
- **Hooks**: Use hooks for local component state and lifecycle (e.g., `useState`, `useEffect`).
- **Components**: Prefer functional components over class components.
- **Props**: Destructure props for clarity and brevity in functional components.

### SQL (Structured Query Language for managing databases)
- **Naming Conventions**:
  - Tables and columns: `snake_case` is common, but conventions can vary (`table_name`, `column_name`)
  - Avoid reserved keywords for identifiers.
- **Queries**:
  - Use explicit `JOIN` clauses instead of implicit joins for clarity.
  - Capitalize SQL keywords (`SELECT`, `FROM`, `WHERE`) for readability.
- **Indexes**: Use indexes strategically for columns often used in `JOIN`, `WHERE`, `ORDER BY`, and `GROUP BY` clauses to improve query performance.
