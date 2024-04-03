# TestingScool, testat în România


# Testing scenarios
## Test cases

| #         |Test Suite | Description     | Expected result |
|---|-------|---------------|------------|
| 1 | Smoke test      | 1. Go to www.login.com. 2. Input valid email and password is entered	Email: testingscool@rtc.ro Password: my$ecr3tP@55    | Login should be successful|

Pros/Cons

Questions testers should answer:
* Why am I running this test?
* What could go wrong?
* What am I looking for?
* What am I testing?
* Which features or areas of product should I cover?
* what problems/risks do I mitigate?
* How long should I test?
* When do I stop?
* How do I know when I'm done?

  
## Charters
Reference: "Explore it!" by Elisabeth Hendrickson, Chapter 2.

Explore (target) With (resources) To discover (information)

* Target: What are you exploring? It could be a feature, a requirement, or a module.
* Resources: What resources will you bring with you? Resources can be anything: a tool, a data set, a technique, a configuration, or perhaps an interdependent feature.
* Information: What kind of information are you hoping to find? Are you characterizing the security, performance, reliability, capability, usability or some other aspect of the system? Are you looking for consistency of design or violations of a standard?

### Examples 
As you learn to write charters, the format will evolve.

* Explore editing profiles with injection attacks to discover security vulnerabilities
* Explore editing profiles with invalid data input to validate Accuracy and correctness of Error Messages
* Explore editing profiles with invalid data input to discover if input validation can be bypassed.
* Explore input fields with JavaScript and SQL injection attacks to discover security vulnerabilities
* Explore Create operations with multiple requests to check for duplication


## Mnemonics
1. Reference: http://karennicolejohnson.com/wp-content/uploads/2012/11/KNJohnson-2012-heuristics-mnemonics.pdf
2. Reference: https://github.com/mlukjanska/testing-cheatsheet/blob/master/Heuristics/testheuristicscheatsheetv1.pdf
3. Testing mnemonics wallpaper: https://findingdeefex.files.wordpress.com/2015/05/testingmnemonics1.jpg?w=1520&h=856

### Product exploration
* On Coverage: SFDPOT by James Bach
* On Regression testing - RCRCRC by Karen Johnson
* On Application touring: -  FCC CUTS VIDS by Michael Kelly https://www.michaeldkelly.com/blog/2005/9/20/touring-heuristic.html
* On Reporting: MCOASTER -  Mission, Coverage,  Obstacles, Audience, Status, Techniques, Environment, Risk by Michael D Kelly

### Mobile testing 
* ISSLICEDUPFUN by Jonathan Kohl - http://www.kohl.ca/articles/ISLICEDUPFUN.pdf


### API Testing
* BINMEN (Gwen Diagram & Ash Winter) - Boundary, Invalid Entries, NULL, Method, Empty, Negative
* POISED (Amber Race) - Parameters, Output, Interop, Security, Errors, Data
* VADER (Stuart Ashman) - Verbs, Authorisation/Authentication, Data, Errors, Responsiveness

## Heuristics
* Variable Analysis
* TouchPoints
* Boundaries
* Goldilocks - Too Big, Too Small, Just Right
* CRUD - Create, Read, Update, Delete
* Follow the Data - Perform a sequence of actions involving data, verifying the data integrity at each step. (Example: Enter → Search → Report → Export → Import → Update → View)* 
