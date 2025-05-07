```
Name : PRAKASH C
Reg.No : 212223240122
```
# RPA_Ex-02

# Aim:
  Get input of name from user and if name is "RAM", Display message as "Welcome Mr. Ramachandran" otherwise "Welcome " followed by Given name. When using Switch case, use different message for every input it gets.

# Algorithm:
## STEP 1:
Create a New Process in UiPath Studio Name it something like SwitchCaseWelcome.

## STEP 2:
Add a Sequence Drag a Sequence to the workflow.

## STEP 3:
Add Input Dialog Activity Label: "Enter your name" Store the result in a variable, e.g., userName of type String.

## STEP 4:
Add Switch Activity Expression: userName.ToUpper (ensures case insensitivity)
      Cases: Case "RAM" → Message Box: "Welcome Mr. Ramachandran"
      Case "JOHN" → Message Box: "Welcome Mr. Johnathan"
      Case "VIJAY" → Message Box: "Welcome Mr. Vijay Kumar"

Default Case → Message Box: "Welcome " + userName

## STEP 5:
Finally,Run it by using F5 key.

# Output:


![Screenshot 2025-05-07 205439](https://github.com/user-attachments/assets/adf0f7c4-3c0d-40f8-8b14-39c9828dd3bb)

![Screenshot 2025-05-07 205522](https://github.com/user-attachments/assets/f5c80f9c-25e9-450e-a48c-a1bff94e1c59)


# Result:
The UiPath workflow executed successfully. It took the user's name as input and used a Switch case to display a personalized welcome message, showing "Welcome Mr. Ramachandran" for "RAM" and a default message for other names.
