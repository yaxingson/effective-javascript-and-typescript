# effective-javascript-and-typescript

English &nbsp; | &nbsp; [Chinese](./README.zh-CN.md)

## JavaScript

### Accustoming Yourself to JavaScript

- [Know Which JavaScript You Are Using]()
- [Understand JavaScript’s Floating-Point Numbers]()
- [Beware of Implicit Coercions]()
- [Prefer Primitives to Object Wrappers]()
- [Avoid using == with Mixed Types]()
- [Learn the Limits of Semicolon Insertion]()
- [Think of Strings As Sequences of 16-Bit Code Units]()

### Variable Scope

- [Minimize Use of the Global Object]()
- [Always Declare Local Variables]()
- [Avoid with]()
- [Get Comfortable with Closures]()
- [Understand Variable Hoisting]()
- [Use Immediately Invoked Function Expressions to Create Local Scopes]()
- [Beware of Unportable Scoping of Named Function Expressions]()
- [Beware of Unportable Scoping of Block-Local Function Declarations]()
- [Avoid Creating Local Variables with eval]()
- [Prefer Indirect eval to Direct eval]()

### Working with Functions

- [Understand the Difference between Function, Method, and Constructor Calls]()
- [Get Comfortable Using Higher-Order Functions]()
- [Use call to Call Methods with a Custom Receiver]()
- [Use apply to Call Functions with Different Numbers of Arguments]()
- [Use arguments to Create Variadic Functions]()
- [Never Modify the arguments Object]()
- [Use a Variable to Save a Reference to arguments]()
- [Use bind to Extract Methods with a Fixed Receiver]()
- [Use bind to Curry Functions)]()
- [Avoid Relying on the toString Method of Functions]()
- [Avoid Nonstandard Stack Inspection Properties]()

### Objects and Prototypes

- [Understand the Difference between prototype, getPrototypeOf, and proto]()
- [Prefer Object.getPrototypeOf to proto]()
- [Never Modify proto]()
- [Make Your Constructors new-Agnostic]()
- [Store Methods on Prototypes]()
- [Use Closures to Store Private Data]()
- [Store Instance State Only on Instance Objects]()
- [Recognize the Implicit Binding of this]()
- [Call Superclass Constructors from Subclass Constructors]()
- [Never Reuse Superclass Property Names]()
- [Avoid Inheriting from Standard Classes]()
- [Treat Prototypes As an Implementation Detail]()
- [Avoid Reckless Monkey-Patching]()

### Arrays and Dictionaries

- [Build Lightweight Dictionaries from Direct Instances of Object]()
- [Use null Prototypes to Prevent Prototype Pollution]()
- [Use hasOwnProperty to Protect Against Prototype Pollution]()
- [Prefer Arrays to Dictionaries for Ordered Collections]()
- [Never Add Enumerable Properties to Object.prototype]()
- [Avoid Modifying an Object during Enumeration]()
- [Prefer for Loops to for...in Loops for Array Iteration]()
- [Prefer Iteration Methods to Loops]()
- [Reuse Generic Array Methods on Array-Like Objects]()
- [Prefer Array Literals to the Array Constructor]()

### Library and API Design

- [Maintain Consistent Conventions]()
- [Treat undefined As “No Value”]()
- [Accept Options Objects for Keyword Arguments]()
- [Avoid Unnecessary State]()
- [Use Structural Typing for Flexible Interfaces]()
- [Distinguish between Array and Array-Like]()
- [Avoid Excessive Coercion]()
- [Support Method Chaining]()

### Concurrency

- [Don’t Block the Event Queue on I/O]()
- [Use Nested or Named Callbacks for Asynchronous Sequencing]()
- [Be Aware of Dropped Errors]()
- [Use Recursion for Asynchronous Loops]()
- [Don’t Block the Event Queue on Computation]()
- [Use a Counter to Perform Concurrent Operations]()
- [Never Call Asynchronous Callbacks Synchronously]()
- [Use Promises for Cleaner Asynchronous Logic]()

## TypeScript

### Getting to Know TypeScript

- [Understand the Relationship Between TypeScript and JavaScript]()
- [Know Which TypeScript Options You're Using]()
- [Understand That Code Generation Is Independent of Types]()
- [Get Comfortable with Structural Typing]()
- [Limit Use of the any Type]()

### TypeScript's Type System

- [Use Your Editor to Interrogate and Explore the Type System]()
- [Think of Types as Sets of Values]()
- [Know How to Tell Whether a Symbol Is in the Type Space or Value Space]()
- [Prefer Type Annotations to Type Assertions]()
- [Avoid Object Wrapper Types (String, Number, Boolean, Symbol, BigInt)]()
- [Distinguish Excess Property Checking from Type Checking]()
- [Apply Types to Entire Function Expressions When Possible]()
- [Know the Differences Between type and interface]()
- [Use readonly to Avoid Errors Associated with Mutation]()
- [Use Type Operations and Generic Types to Avoid Repeating Yourself]()
- [Prefer More Precise Alternatives to Index Signatures]()
- [Avoid Numeric Index Signatures]()

### Type Inference and Control Flow Analysis

- [Avoid Cluttering Your Code with Inferable Types]()
- [Use Different Variables for Different Types]()
- [Understand How a Variable Gets Its Type]()
- [Create Objects All at Once]()
- [Understand Type Narrowing]()
- [Be Consistent in Your Use of Aliases]()
- [Understand How Context Is Used in Type Inference]()
- [Understand Evolving Types]()
- [Use Functional Constructs and Libraries to Help Types Flow]()
- [Use async Functions Instead of Callbacks to Improve Type Flow]()
- [Use Classes and Currying to Create New Inference Sites]()

### Type Design

- [Be Liberal in What You Accept and Strict in What You Produce]()
- [Prefer Types That Always Represent Valid States]()
- [Don’t Repeat Type Information in Documentation]()
- [Avoid Including null or undefined in Type Aliases]()
- [Push Null Values to the Perimeter of Your Types]()
- [Prefer Unions of Interfaces to Interfaces with Unions]()
- [Prefer More Precise Alternatives to String Types]()
- [Use a Distinct Type for Special Values]()
- [Limit the Use of Optional Properties]()
- [Avoid Repeated Parameters of the Same Type]()
- [Prefer Unifying Types to Modeling Differences]()
- [Prefer Imprecise Types to Inaccurate Types]()
- [Name Types Using the Language of Your Problem Domain]()
- [Avoid Types Based on Anecdotal Data]()

### Unsoundness and the any Type
]()
- [Use the Narrowest Possible Scope for any Types]()
- [Prefer More Precise Variants of any to Plain any]()
- [Hide Unsafe Type Assertions in Well-Typed Functions]()
- [Use unknown Instead of any for Values with an Unknown Type]()
- [Prefer Type-Safe Approaches to Monkey Patching]()
- [Avoid Soundness Traps]()
- [Track Your Type Coverage to Prevent Regressions in Type Safety]()

### Generics and Type-Level Programming

- [Think of Generics as Functions Between Types]()
- [Avoid Unnecessary Type Parameters]()
- [Prefer Conditional Types to Overload Signatures]()
- [Know How to Control the Distribution of Unions over Conditional Types]()
- [Use Template Literal Types to Model DSLs and Relationships Between Strings]()
- [Write Tests for Your Types]()
- [Pay Attention to How Types Display]()
- [Prefer Tail-Recursive Generic Types]()
- [Consider Codegen as an Alternative to Complex Types]()

### TypeScript Recipes

- [Use never Types to Perform Exhaustiveness Checking]()
- [Know How to Iterate Over Objects]()
- [Use Record Types to Keep Values in Sync]()
- [Use Rest Parameters and Tuple Types to Model Variadic Functions]()
- [Use Optional never Properties to Model Exclusive Or]()
- [Consider Brands for Nominal Typing]()

### Type Declarations and @types

- [Put TypeScript and @types in devDependencies]()
- [Understand the Three Versions Involved in Type Declarations]()
- [Export All Types That Appear in Public APIs]()
- [Use TSDoc for API Comments]()
- [Provide a Type for this in Callbacks if It's Part of Their API]()
- [Mirror Types to Sever Dependencies]()
- [Use Module Augmentation to Improve Types]()

### Writing and Running Your Code

- [Prefer ECMAScript Features to TypeScript Features]()
- [Use Source Maps to Debug TypeScript]()
- [Know How to Reconstruct Types at Runtime]()
- [Understand the DOM Hierarchy]()
- [Create an Accurate Model of Your Environment]()
- [Understand the Relationship Between Type Checking and Unit Testing]()
- [Pay Attention to Compiler Performance]()

### Modernization and Migration

- [Write Modern JavaScript]()
- [Use @ts-check and JSDoc to Experiment with TypeScript]()
- [Use allowJs to Mix TypeScript and JavaScript]()
- [Convert Module by Module Up Your Dependency Graph]()
- [Don't Consider Migration Complete Until You Enable noImplicitAny]()
