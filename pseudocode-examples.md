# Example of Pseudocode vs Real Code:

## Example 1 - Basic Login Logic

#### Pseudocode:
```
START
Check if the user is logged in
IF logged in
    Display user dashboard
ELSE
    Display login page
END
```

#### Python Code (real):
```python
if user.is_logged_in():
    display_dashboard(user)
else:
    display_login_page()
```

#### JavaScript Code (real)
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

#### C# Code (real)
```c#
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
---

## Example 2 - Variable & While Loop


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

- **Explanation**:
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

- **Explanation**:
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

- **Explanation**:
  - In JavaScript, the `console.log(i);` statement is used to print the value of `i` to the console.
  - A `while` loop runs as long as `i` is less than or equal to 5, incrementing `i` by 1 after each iteration.

Each language handles the loop and printing in a slightly different way, but they all follow the same logic outlined in the pseudocode.