# RPA_Ex-01
# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  Get input of name from user and if name is "RAM", Display message as "Welcome Mr. Ramachandran" otherwise "Welcome " followed by Given name. When using Switch case, use different message for every input it gets.

# Algorithm:
STEP 1:Create a New Process in UiPath Studio Name it something like SwitchCaseWelcome.

STEP 2:Add a Sequence Drag a Sequence to the workflow.

STEP 3:Add Input Dialog Activity Label: "Enter your name" Store the result in a variable, e.g., userName of type String.

STEP 4:Add Switch Activity Expression: userName.ToUpper (ensures case insensitivity)
      Cases: Case "RAM" → Message Box: "Welcome Mr. Ramachandran"
      Case "JOHN" → Message Box: "Welcome Mr. Johnathan"
      Case "VIJAY" → Message Box: "Welcome Mr. Vijay Kumar"

Default Case → Message Box: "Welcome " + userName
STEP 5:Include Necessary parameters in each functions.


# Result:
Thus, the Data Visualization using seaborn python library for the given data is implemented successfully.
