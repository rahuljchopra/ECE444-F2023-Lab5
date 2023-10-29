# ECE444-F2023-Lab5

Activity 1: Completed Flaskr - a simple blogging app

***

Activity 2: Writing Unit Test Functions
1. Implemented **client()** function which is a pytest fixture
2. Implemented **test_index()** function to test if the home page is accessible
3. Implemented **test_register_success(client)** function to test if a new user can successfully register
   
Link to the unit test functions: https://github.com/ECE444-2023Fall/project-1-web-application-design-group9-netninjas/blob/main/tests/app_test.py#L5-L36

***

Activity 3: What are the pros and cons of TDD?

**Pros of TDD**

- Improved Code Quality: TDD helps to ensure the code meets its requirements by validating it through continuous testing, which leads to fewer defects and higher code quality.
- Early Bug Detection: TDD encourages early detection of bugs, which can reduce the cost of fixing issues discovered later in the development process.
- Documentation: The tests serve as a form of documentation, showcasing how the code is expected to work, which is helpful for other developers who work on the codebase.
- Better Design: TDD often leads to more modular, loosely coupled, and maintainable code because it was designed with testing in mind.
- Faster Debugging: When a test fails, it's easier to identify the cause of the problem because the failing test pinpoints the issue, speeding up the debugging process.

**Cons of TDD**

- Learning Curve: TDD can be challenging for developers new to this practice, and it may take some time to become proficient.
- Upfront Time Investment: Writing tests before writing code can initially slow down the development process, which can be a concern for projects with tight deadlines.
- Test Maintenance: Maintaining the test suite alongside the codebase requires ongoing effort, and poorly maintained tests can become a liability.
- Overemphasis on Testing: TDD can lead to an overemphasis on writing tests at the expense of other important aspects of software development, such as usability and performance.
