# Dumpify
Improve productivity and debuggability by a `.Dump()` extension methods to **Console Applications**, similar to LinqPad's.

One of my favorites LinqPad feature is its `.Dump()` extension methods and how customizable they are, and it was always hard to return to Visual Studio and find out this features doesn't exist there.

# Features
* Dump any object
* Support for Arrays and IEnumerables
* Support for Custom descriptors
* Support for max nesting levels
* Configurable
* Spectre.Console renderers
* Special Handling for:
    * Arrays
    * MultiDimentional Arrays
    * StringBuilder
    * Dictionary<T, K>

# How to use
Either use `dotnet add package Dumpify` or `Install-Package Dumpify`

# To do
* Custom Outputs
* Improve Cache By decoupling the PropertyInfo from the Descriptors.
* Rethink Generators caching keys.
* Consider using Max Nesting for Descriptors
* Refactor Renderers and make it better extendable
* Better styling
* Custom styling
* Add more renderers
    * JavaScript's `console.log` style
* Decouple from Spectre.Console    
* Tests
    * More tests
    * Visual (Render) Tests - consider acceptance tests
    * Tests for Nesting

# Disclaimer
This project is inspired by LinqPad's Dump features, authored by Joseph Albahari.
