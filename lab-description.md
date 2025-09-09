# Lab 08 Instructions

1. Follow the slides on [CI/CD and Mocking](./slides/lab8-ci-cd-mocking.pdf)

2. Follow the instructions on [lab-instructions](./lab-instructions.md) along with the TA.

3. Complete Lab Exercise.  

# Lab 08 Participation Exercise

Proper completion of this exercise is considered as part of course participation.

1. Create an issue and a branch on your repository to implement this feature for.

2. Implement a new feature for the app to make that movies have unique titles. You will need to modify the `MovieProvider.java` to check with the database is a movie with that name already exisits. You also must give feedback to the user with an error message **before closing the dialogue window** for adding/editing a movie.

3. Add one (or more) JUnit tests with a mock to test this new functionality.

4. Implement a UI test in the `MainActivityTest.java` file to try to adding a duplicate movie and check that the error message is displayed to the user.

5. Make a PR to main from your branch and ensure that the CI/CD pipeline passes before merging your branch into main.
