# JSDoc Style Guide for Project

The codebase follows these JSDoc documentation patterns:

1. File Level Documentation
- Start each file with @file tag describing the file's purpose
- Include @module to define the module name
- List all dependencies with @requires tags
- Example:
        /**
         * @file Handles click event listening and text editing functionality
         * @module TextEditor
         * @requires DOMService
         */

2. Constants and Configuration
- Use @constant for all constant values
- Include type information in curly braces
- Add descriptive comments for each constant's purpose
- For complex objects, define custom @typedef definitions with detailed @property descriptions

3. Classes
- Mark with @class tag
- Include @constructor for constructor methods
- Include a concise class description
- Document all methods with:
  - Access level (@private or @public) 
  - @param for each parameter with type in curly braces
  - @returns when method returns a value
  - Brief description of method's purpose

4. Methods/Functions
- Each method has a single-line description
- Complex parameters use object destructuring documentation
- Private methods marked with @private
- Static methods marked with @static
- Return values always documented when present
- Use @callback for function type definitions passed as parameters

5. Type Definitions
- Complex types defined using @typedef
- Each property documented with @property
- Nested objects fully documented with types
- Function types documented with parameter and return types

6. Future Improvements
- Mark planned enhancements with @todo
- Include specific details about what needs to be done
- Example:
        /**
         * @todo Implement caching for repeated operations
         * @todo Add error handling for network failures
         */

7. Format
- Consistent indentation in multi-line comments
- Empty line between major comment sections
- Types always in curly braces
- Clear separation between description and tags

Example:
        /**
         * @typedef {Object} Config
         * @property {Object} attributes - Custom data attributes
         * @property {string} attributes.highlight - Data attribute name
         */