# Introduction to Coding Guidelines for Cocoa

Developing a Cocoa framework, plug-in, or other executable with a public API requires some approaches and conventions that are different from those used in application development. The primary clients of your product are developers, and it is important that they are not mystified by your programmatic interface. This is where API naming conventions come in handy, for they help you to make your interfaces consistent and clear. There are also programming techniques that are special to—or of greater importance with—frameworks, such as versioning, binary compatibility, error-handling, and memory management. This topic includes information on both Cocoa naming conventions and recommended programming practices for frameworks.

# Organization of This Document

The articles contained in this topic fall into two general types. The first and larger group presents naming conventions for programmatic interfaces. These are the same conventions (with some minor exceptions) that Apple uses for its own Cocoa frameworks. These articles on naming conventions include the following:

- Code Naming Basics
- Naming Methods
- Naming Functions
- Naming Properties and Data Types
- Acceptable Abbreviations and Acronyms

The second group (currently with a membership of one) discusses aspects of framework programming:

- Tips and Techniques for Framework Developers
