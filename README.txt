# My Website

This repository contains the codebase for my projects that demonstrate my skills. Below is an overview of the website structure to help guide you.

## Folder Structure

The folders are organized according to the sections of the page, according to their respective categories.

### Website Mapping

| Section Name          | Important Files            | Description         |
|------------------|---------------------------|-------------------------------------------------------------------------------------------------------------
| Forgot Password  | Workout_Forgot          | Check_Code.php checks the reset code sent to the user's email and compares it to the one in the database. ConfirmNewPassword.php updates the user's password in the database after confirmation. ForgotPasswordPage.php allows users to request a password reset. LinkConfirmation.php confirms the reset link sent via email. ReEnter.php prompts the user to re-enter their password for confirmation. ResetPassword.php provides a form for the user to input a new password. ResetSuccessConfirmation.php displays a success message after a successful password reset. Send_Email.php handles sending the password reset email to the user. | This is the functionality to change a password if you forget what your current password is.                                                                  |
| Friends          | Workout_Friends         | Friends.php is the frontend that displays the user's friends list and allows interactions such as viewing friend profiles and sending friend requests. Friendsbackend.php manages the backend functionalities like adding friends, accepting requests, and retrieving friend data for display on the frontend. | This page allows users to view and manage their friends list, send friend requests, and interact with other users on the platform.                          |
| Login Page       | Workout_Login           | Login.php provides the frontend for users to enter their login credentials and access the platform. Login_Backend.php checks the entered credentials against the database to confirm user identity. Verify_Account.php contains a function that retrieves the user's current email from the id contained in the Authentication Token. Al_logo.png is the logo displayed on the login page, representing the "Athletic Legs" brand with a dumbbell icon. | This page allows users to log into their accounts securely and access their workout-related features.                                                        |
