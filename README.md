# QA_Check-List
Check-list for facebook.com app (Log In, Sign Up, Forgot Password functions)

# Log In

1.	Verify location of “Long In” function and its components: “Email or Phone Number” text field, “Password” text field, “Log In” button.
2.	Verify when entering the homepage of the site the cursor is located on the “Email or Phone Number” text field by default.
3.	Verify "Log In" button is clickable.
4.	Verify there is a validation message if to log in with empty fields.
5.	Verify that “Email or Phone Number” and “Password” text fields have a valid placeholder.

# “Email or Phone Number” text field

6.	Verify Emails for “Email or Phone Number” text field with valid format are allowed.
7.	Verify Emails for “Email or Phone Number” text field with invalid format are not allowed.
8.	Verify phone numbers for “Email or Phone Number” text field with valid format are allowed.
9.	Verify phone numbers for “Email or Phone Number” text field with invalid format are not allowed.
10.	Verify the “Email or Phone Number” text field is allowed for the input: Latin letters, digits, spec symbols.
11.	Verify the “Email or Phone Number” text field is not allowed for the input tags (<script>alert('test script entered into the [fieldname]')</script>)
12.	Verify the “Email or Phone Number” text field is not allowed for the input wildcards and accented chars.
13.	Verify the “Email or Phone Number” text field is not allowed for the input files formats.
14.	Verify a maximum length of the symbols for the “Email or Phone Number” text field
15.	Verify a minimum length of the symbols for the “Email or Phone Number” text field
16.	Verify there is a validation message for the maximum + 1 symbol for the “Email or Phone Number” text field
17.	Verify a maximum – 1 symbol for the “Email or Phone Number” text field
18.	Verify spaces in “Email or Phone Number” text field are truncated at the beginning and at the end of the text.
19.	Verify spaces in “Email or Phone Number” text field are not truncated in the middle of the text.
20.	Verify there is a validation message for the empty “Email or Phone Number” text field

# “Password” text field

21.	Verify it is possible to log in with correct password.
22.	Verify there is a verification message if to log in with incorrect password.
23.	Verify there is a validation message for empty “Password” text field.
24.	Verify a maximum length of the symbols for the “Password” text field
25.	Verify a minimum length of the symbols for the “Password” text field
26.	Verify there is a validation message for the maximum + 1 symbol for the “Password” text field
27.	Verify a maximum – 1 symbol for the “Password” text field
28.	Verify the “Password” text field is allowed for the input: Latin letters, Russian letters, digits, lower-case letters, upper-case letters, spec symbols.
29.	Verify spaces in “Password” text field are not truncated they should be recognized as the part of password.
30.	Verify the “Password” text field is not allowed for the input tags (<script>alert('test script entered into the [fieldname]')</script>)
31.	Verify the “Password” text field is not allowed for the input wildcards and accented chars.
32.	Verify it is possible to copy-pasted the password.
33.	Verify that User is redirected to appropriate page after successful login

  # Create a New Account
  
1.	Verify “Create a New Account” button is active
2.	Verify the “Sign Up” pop up window is displayed after clicking the " Create a New Account" button.
3.	Verify the content of the “Sign Up” pop up window
4.	Verify “Sign Up” button is active

  # “First name” text field

1.	Verify “First name” text field with valid format is allowed.
2.	Verify “First name” text field with invalid format is not allowed.
3.	Verify a maximum length of the symbols for the “First name”” text field
4.	Verify a minimum length of the symbols for the “First name” text field
5.	Verify there is a validation message for the maximum + 1 symbol for the “First name” text field
6.	Verify a maximum – 1 symbol for the “First name” text field
7.	Verify spaces in “First name” text field are truncated at the beginning and at the end of the text.
8.	Verify spaces in “First name” text field are not truncated in the middle of the text.
9.	Verify there is a validation message for the empty “First name” text field
10.	Verify it is possible to enter digits, letters, and spec symbols in to the “First name” text field
11.	Verify the “First name” text field is not allowed for the input wildcards, tags, and accented chars.

  # “Last name” text field

12.	Verify “Last name” text field with valid format is allowed.
13.	Verify “Last name” text field with invalid format is not allowed.
14.	Verify a maximum length of the symbols for the “Last name”” text field
15.	Verify a minimum length of the symbols for the “Last name” text field
16.	Verify there is a validation message for the maximum + 1 symbol for the “Last name” text field
17.	Verify a maximum – 1 symbol for the “Last name” text field
18.	Verify spaces in “Last name” text field are truncated at the beginning and at the end of the text.
19.	Verify spaces in “Last name” text field are not truncated in the middle of the text.
20.	Verify there is a validation message for the empty “Last name” text field
21.	Verify it is possible to enter digits, letters, and spec symbols in to the “Last name” text field
22.	Verify the “Last name” text field is not allowed for the input wildcards, tags, and accented chars.

  # “Mobile number or email” text field

34.	Verify Emails for “Mobile number or email” text field with valid format are allowed.
35.	Verify Emails for “Mobile number or email” text field with invalid format are not allowed.
36.	Verify phone numbers for “Mobile number or email” text field with valid format are allowed.
37.	Verify phone numbers for “Mobile number or email” text field with invalid format are not allowed.
38.	Verify the “Mobile number or email” text field is allowed for the input: Latin letters, digits, spec symbols.
39.	Verify the “Mobile number or email” text field is not allowed for the input tags (<script>alert ('test script entered into the [fieldname]’) </script>)
40.	Verify the “Mobile number or email” text field is not allowed for the input wildcards and accented chars.
41.	Verify the “Mobile number or email” text field is not allowed for the input files formats.
42.	Verify a maximum length of the symbols for the “Mobile number or email” text field
43.	Verify a minimum length of the symbols for the “Mobile number or email” text field
44.	Verify there is a validation message for the maximum + 1 symbol for the “Mobile number or email” text field
45.	Verify a maximum – 1 symbol for the “Mobile number or email” text field
46.	Verify spaces in “Mobile number or email” text field are truncated at the beginning and at the end of the text.
47.	Verify spaces in “Mobile number or email” text field are not truncated in the middle of the text.
48.	Verify there is a validation message for the empty “Mobile number or email” text field

  # “New password” text field

49.	Verify there is a validation message for empty “New password” text field.
50.	Verify a maximum length of the symbols for the “New password” text field.
51.	Verify a minimum length of the symbols for the “New password” text field.
52.	Verify there is a validation message for the maximum + 1 symbol for the “New password” text field.
53.	Verify a maximum – 1 symbol for the “New password” text field.
54.	Verify the “New password” text field is allowed for the input: Latin letters, Russian letters, digits, lower-case letters, upper-case letters, spec symbols.
55.	Verify spaces in “New password” text field are not truncated they should be recognized as the part of password.
56.	Verify the “New password” text field is not allowed for the input tags (<script>alert('test script entered into the [fieldname]')</script>).
57.	Verify the “New password” text field is not allowed for the input wildcards and accented chars.
58.	Verify it is possible to copy-pasted the password.
59.	Verify that the password is in encrypted form when entered.

  # “Birthday” drop-downs

60.	Verify that the current date is set by default.
61.	Verify it is possible to enter a valid date of birth.
62.	Verify a validation icon appears, if the date of birth is greater than current date.
63.	Verify it is impossible to choose several values from the drop-downs.
64.	Verify it is impossible to leave the drop-downs empty.
65.	Verify a validation icon appears, if to choose incorrect “Date” values for the month ‘February’ (e.g. 30-31 February).
66.	Verify drop-down "Month" opens and contains the list of months to select.
67.	Verify drop-down "Day" opens and contains the list of dates to select.
68.	Verify drop-down "Year" opens and contains the list of years to select.
69.	Verify values from the "Month", "Day", "Year" drop-downs may be preselected by arrow keys and then selected by "Enter".
72. Verify values from the "Month", "Day", "Year" drop-downs may be preselected by entering the first letter from the keyboard.

  # “Gender” radio buttons

73.	Verify the alignment of the radio button control on the form.
74.	67.	Verify that you can select only one radio button (“Female”, “Male”, “Other”)
75.	Verify a warning icon appears for empty radio buttons
76.	Verify a multiple radio buttons choice is impossible.

  # Forgot Password

77.	Verify location of the “Forgot password” link
78.	71.	Verify the “Forgot password” link is active and redirect to the “Restore password” page.
79.	Verify if the link to change the password is sent to the user’s registered email or phone only.
80.	Check for user authentication and authorization availability. 
81.	Verify if the new password matches with required specifications for characters (e.g. special characters, digits, etc.)
82.	Verify if the login is possible with the newly changed password.
