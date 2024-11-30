# SEG2505-Tutorial5

This repository contains the results of the **fifth tutorial assignment** for SEG2505, which focuses on writing unit and UI tests for an Android application. The exercise involves testing a login activity with both **JUnit** for validating user input and **Espresso** for verifying UI behavior when incorrect data is entered.

## Assignment Overview

In this tutorial, we focused on the following tasks:

1. **Write a JUnit test to validate the values entered in the login form**  
   The goal was to create unit tests that ensure the correctness of user input, such as validating the format of the email and checking the minimum length of the password.

2. **Write an Espresso test to verify UI behavior when invalid values are entered**  
   The task involved creating an Espresso test to simulate user interactions, particularly checking that the application displays the correct error message ("Valeur incorrecte") when invalid input is detected.

This exercise helps to develop essential skills in testing Android applications, including both unit tests for logic validation and UI tests for behavior validation.

### Subdirectory Breakdown

1. **MainActivity.java**  
   This is the main activity of the application. It contains the user login form with the following input fields:  
   - First name  
   - Last name  
   - Email  
   - Password  
   - Submit button  
   
   There is also a `TextView` to display error messages when the input values are invalid.

2. **LoginFormTest.java**  
   This file contains **JUnit tests** to validate the data entered by the user in the login form. It checks if the input values are valid, such as verifying that the email is correctly formatted and ensuring the password meets the minimum length requirement.

3. **LoginFormEspressoTest.java**  
   This file contains **Espresso UI tests** that simulate user actions. The tests focus on checking that when invalid input is entered into the form, the app correctly displays an error message, specifically the "Valeur incorrecte" text in the `TextView`.

### For Teaching Assistants

To review the work, please access the repository at the following link:
[SEG2505-Tutorial5](https://github.com/qerope/seg2505-tutorial5)

Feel free to navigate through the subdirectories to review the code for each part of the exercise. You can also run the tests to verify the correctness of the implementation.

### Submission Instructions

1. A ZIP file containing the clone of this repository, including the `README` file, must be submitted on **BrightSpace**.
2. The `README` file should include a link to this GitHub repository for easy access and review.

## Conclusion

This repository contains the work completed for **SEG2505-Tutorial5**, where we focused on testing Android applications using **JUnit** and **Espresso**. We wrote unit tests to validate user input and UI tests to ensure proper error messages are displayed when invalid values are entered in a login form.

Please reach out if you have any questions or need further clarification on any part of the tutorial or tests.
