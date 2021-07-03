### Intro to modular design

#### Notes

##### Day 1
1. Separation of concerns and the importance of drawing a Dependency diagram.
2. Once the separation achieved, we can make use of macOS target to test API + Database layer.
3. Single/Bi-directional is important to understand.
4. You need to trailor your own need (by following the correct principle/pattern).

##### Day 2
1. All architectures are good but a good architecture solves a problem (good architecture balances the trade-off and defines clear boundaries).
2. Good requirement == good architecture (Bad architecture starts with assumptions).
3. Some traits of a good architecture are:
   - Welcome requirement changes
   - Improve estimation accuracy
   - Make testing easier
   - Allow independent development (and deployment, and testing in isolation/parallel)
   - Make it easier to maintain a fast and constant pace
   - Increase the number of reusable components
4. Some traits of good requirements
   - happy and the sad paths
   - No assumptions

##### Day 3
Singletons
- When and Why
- Better alternatives
- Refactoring steps to gradually remove tight coupling created by singletons
Controlling your dependencies: 
- Locating globally shared instances (Implicit) vs. Injecting dependencies (Explicit)
- Dependency injection

##### Day 4
- Understand the trade-offs of access control for testing purposes
- Expand behavior checking (and coverage) using test spy objects
- Test visibility: public vs @testable (internal)

#### Homework

##### Day 1
1. Monolithic architecture?
2. How to draw Dependency/UML diagram.

##### Day 2
1. Story writing template.
