# Copilot Instructions for Rajapinnat_ Project

## Project Overview
This is a minimal JavaScript project demonstrating basic data structure usage with an array of book objects. The project contains a single file (`bookArray.js`) that defines book data and performs console logging operations.

## Core Architecture

### Data Structure
- **Books Array**: A constant `bookData` containing book objects with properties:
  - `id_book`: String identifier (e.g., '1', '2', '3')
  - `name`: Book title (e.g., "C++", "Java")
  - `author`: Author name
  - `isbn`: ISBN-10/13 format string

### Current Functionality
- `bookArray.js`: Defines a static array of 3 books and logs the entire array and first book to console

## Code Conventions & Patterns

### Object Property Naming
- Mixed quote styles in object literals (single and double quotes used interchangeably)
- Snake_case for property names (`id_book`)
- String values for all properties (including IDs and numeric-like data)

### Console Output Pattern
Current approach: Direct `console.log()` calls for debugging. When extending, consider if a logging utility would be beneficial.

## Development Workflow

### Running the Project
```bash
node bookArray.js
```

### Extending the Codebase
When adding features:
1. Maintain the existing array structure unless refactoring is explicitly requested
2. Keep property naming consistent with existing conventions
3. Test new functionality via `node bookArray.js` or similar execution

## Integration Points
- No external dependencies currently
- No build process required
- Runs directly with Node.js

## Common Tasks
- **Adding Books**: Extend `bookData` array with new object entries
- **Data Retrieval**: Access via index (e.g., `bookData[0]`) or implement filtering functions
- **Output**: Currently uses `console.log()` for all output

---
*Last updated: December 2025*
