## Student Name

**Instructor:** Andrew

**Repo URL:** github.com/thompickett/crypto.rb

**Notes:**
Project does not run via command line- encrypt decrypt or crack.

Not a lot to show from this project so it's hard to draw a major conclusion. There was some separation of logical components, but some leakage in encrypt. Encrypt had decrypting going on too.



## Evaluation Rubric

The project will be assessed with the following rubric:

### 1. Overall Functionality - 1

* 4: Application follows the complete spec and one extension
* 3: Application encrypts, decrypts, and cracks files as described
* 2: Application is missing one of the three operations
* 1: Application is missing two operations or crashes during normal usage

### 2. Fundamental Ruby & Style - 2.5

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.
* 2:  Application runs but the code has many long methods (>8 lines) and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 3. Test-Driven Development - 1.5 - not a lot of tests, but the ones that are there do test come core functionality.

* 4: Application is broken into components which are well tested in both isolation and integration
* 3: Application uses tests to exercise core functionality, but has some gaps in coverage or leaves edge cases untested.
* 2: Application tests some components but has many gaps in coverage.
* 1: Application does not demonstrate strong use of TDD

### 4. Breaking Logic into Components - 2

* 4: Application effectively breaks logical components apart with clear intent and usage
* 3: Application has multiple components with defined responsibilities but there is some leaking of responsibilities
* 2: Application has some logical components but divisions of responsibility are inconsistent or unclear and/or there is a "God" object taking too much responsibility
* 1: Application logic shows poor decomposition with too much logic mashed together
