## Description
A few sentences describing the overall goals of the pull request's commits.

___

- [ ] Produced code passes tests
- [ ] Code builds without errors
- [ ] Unit tests written and passing

  * Clear and easy to understand
  * Reliable that they fail if a bug is in the system
  * Fast (slow tests will be a nuisance in numbers)
        
- [ ] Code is documented

    * When doing public API functionality context of the code is written
    * Clarification, when code might be unclear.
    * Clear and well named functionality does not need a comment
      
- [ ] Variable names convey their use case
- [ ] Produced code matches presumed functionality

    * Matches specifications given in the issue
    * Works in desired environments
      
- [ ] Code quality

    * Code follows best practices
      * Usually specified by the language, framework or library itself.
    * Code follows styleguide
    * Project specific linter rules
      * If no linting rules are specified each project should follow some kind of guidelines for unified code
        
- [ ] Functionality verified by testing the application
- [ ] Each function and class should have a single clear purpose

    * Complex or long function sections should be split into smaller ones
    * Each additional **if**, **loop**, **switch** and **logical conditional operation** adds complexity
    * Complexity can be measured by this way if each complexity point is added together.
