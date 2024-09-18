# Pseudocode vs Real Code Examples:

## Example 1 - Basic Login Logic

Check if a user is logged in and display either a dashboard or a login page based on their login status.

### Pseudocode:
```
START
Check if the user is logged in
IF logged in
    Display user dashboard
ELSE
    Display login page
END
```

### Python Code (real):
```python
if user.is_logged_in():
    display_dashboard(user)
else:
    display_login_page()
```

**Explanation**: 

- The code checks if the user is logged in using a method `is_logged_in()` on the `user` object. 
- If the user is logged in, their personalized dashboard is displayed using the `display_dashboard()` function.
- If they are not logged in, the `display_login_page()` function is called to show the login screen.

---

### **JavaScript Example**:
```javascript
// Check if the user is logged in
if (user.isLoggedIn()) {
    // Display user dashboard
    displayDashboard(user);
} else {
    // Display login page
    displayLoginPage();
}
```

**Explanation**: 
- The `user.isLoggedIn()` function checks if the user is logged in.
- If the user is logged in, the `displayDashboard(user)` function is called to display the dashboard.
- Otherwise, the `displayLoginPage()` function is called to display the login page.

---

### **C# Example**:
```csharp
// Check if the user is logged in
if (user.IsLoggedIn())
{
    // Display user dashboard
    DisplayDashboard(user);
}
else
{
    // Display login page
    DisplayLoginPage();
}
```

**Explanation**: 
- `IsLoggedIn()` is a method that checks if the user is logged in.
- `DisplayDashboard(user)` is called if the user is logged in, and `DisplayLoginPage()` is called otherwise.

---

## Example 2 - Variable & While Loop

Use a variable and a loop to output numbers from 1 to 5.

### **Pseudocode**:
```
START
Set variable 'i' to 1
WHILE 'i' is less than or equal to 5
    Print 'i'
    Increment 'i' by 1
END WHILE
END
```

---

### **Python Example**:
```python
# Set variable i to 1
i = 1

# While i is less than or equal to 5
while i <= 5:
    # Print i
    print(i)
    # Increment i by 1
    i += 1
```

**Explanation**:
- A `while` loop is used to print the value of `i` from 1 to 5.
- The loop continues as long as `i` is less than or equal to 5.
- The variable `i` is incremented by 1 in each iteration.

---

### **C# Example**:
```csharp
// Set variable i to 1
int i = 1;

// While i is less than or equal to 5
while (i <= 5)
{
    // Print i
    Console.WriteLine(i);
    // Increment i by 1
    i++;
}
```

**Explanation**:
- Similar to Python, a `while` loop is used.
- The `Console.WriteLine(i);` statement prints the value of `i` in each iteration.
- The variable `i` is incremented by 1 using `i++`.

---

### **JavaScript Example**:
```javascript
// Set variable i to 1
let i = 1;

// While i is less than or equal to 5
while (i <= 5) {
    // Print i
    console.log(i);
    // Increment i by 1
    i++;
}
```

**Explanation**:
- In JavaScript, the `console.log(i);` statement is used to print the value of `i` to the console.
- A `while` loop runs as long as `i` is less than or equal to 5, incrementing `i` by 1 after each iteration.

Each language handles the loop and printing in a slightly different way, but they all follow the same logic outlined in the pseudocode.
