# Equivalence Classes

You are evaluating a system that requires a user to login with a "strong" password. The password must satisfy the following requirements:

1.	Minimum length: 12 characters
2.	At least one uppercase character
3.	At least one number
4.	At least one special symbol

Your goal is to combinatorially test the `resetPassword` function:

`boolean resetPassword (String newPwd);`

The `resetPassword` function takes a string as an input and returns true if the password meets the above requirements. If the password does not meet stated requirements, then the new password is rejected and `resetPassword` returns false. 

1. Use each constraint to partition the input space into equivalence classes
2. Use weak robust equivalence class testing to create a set of test cases. 
