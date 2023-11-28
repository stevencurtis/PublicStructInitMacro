# Macros

## Type of macros
**Expression Macros**
These macros are used as expressions in the source code, marked with #, and are expanded into expressions. They can have parameters and a result type, similar to functions, and describe the effect of the macro expansion on the expression.
**Freestanding Declaration Macros**
These macros extend the notion of freestanding macros to allow macros to introduce new declarations. They are also expanded using the # syntax and can be used anywhere a declaration is provided. Unlike expression macros, they never produce a value.
**Attached Macros**
These macros enable extending Swift by creating and extending declarations based on syntactic transformations of their arguments. They help in building expressive libraries and eliminating extraneous boilerplate.


## Resources
[https://swift-ast-explorer.com](https://swift-ast-explorer.com)
[https://github.com/krzysztofzablocki/Swift-Macros](https://github.com/krzysztofzablocki/Swift-Macros)
[https://developer.apple.com/videos/play/wwdc2023-10166](https://developer.apple.com/videos/play/wwdc2023-10166)
