# Creating an Application in Salesforce.com using Apex Programming Language

## Aim
To create and execute a simple Apex program in Salesforce Developer Console using Apex Programming Language.

---

# Software Requirements
- Internet Connection
- Web Browser (Chrome / Edge / Firefox)
- Salesforce Developer Account

---

# Theory
Salesforce is a cloud-based CRM platform used for application development and business process automation.

Apex is an object-oriented programming language developed by Salesforce. It is used to execute flow and transaction control statements on the Salesforce platform server.

Developer Console is an IDE provided by Salesforce to write, compile, execute, and debug Apex code.

---

# Steps to Perform the Practical

## Step 1: Create Salesforce Developer Account
1. Open the Salesforce Developer Signup page:
   https://developer.salesforce.com/signup

2. Fill in the required details:
   - Name
   - Email
   - Username
   - Company Name

3. Verify your email and log in to Salesforce.

---

## Step 2: Open Developer Console
1. After login, open the Salesforce Dashboard.
2. Click on the **Setup (⚙️ Gear Icon)** available at the upper-right corner.
3. Select **Developer Console** from the dropdown menu.

---

## Step 3: Create a New Apex Class
1. In Developer Console click:
   - File
   - New
   - Apex Class

2. Enter the class name.

Example:
```apex
test
```

3. Click on **OK**.

---

## Step 4: Write Apex Program

Write the following Apex code and save the file.

## Apex Program
```apex
public class test {

    public static void perinfo() {

        system.debug('***************');
        system.debug('Student Details');
        system.debug('***************');

        String n = 'Krushna Patil';
        String b = 'Computer Engineering Department';

        String year = '3rd Year';
        String div = 'B';

        Integer roll = 31;

        system.debug('Name :' + n);
        system.debug('Branch :' + b);
        system.debug('Class :' + year);
        system.debug('Division :' + div);
        system.debug('Roll No :' + roll);
    }
}
```

---

# Explanation of Code

| Statement | Description |
|----------|-------------|
| `public class test` | Declares a class named `test` |
| `public static void perinfo()` | Static method to display student information |
| `system.debug()` | Prints output in Debug Log |
| `String` | Stores text values |
| `Integer` | Stores numeric values |

---

# Step 5: Execute the Program
1. In Developer Console click:
   - Debug
   - Open Execute Anonymous Window

2. A popup window will appear.

3. Write the following statement:
```apex
test.perinfo();
```

4. Check the option:
```text
Open Log
```

5. Click on the **Execute** button.

---

# Step 6: View Output
1. Debug Log will open automatically after execution.
2. Click on:
```text
Debug Only
```

3. The output will display student details.

---

# Expected Output
```text
***************
Student Details
***************
Name : Krushna Patil
Branch : Computer Engineering Department
Class : 3rd Year
Division : B
Roll No : 31
```

---

# Result
The Apex program was successfully created and executed in Salesforce Developer Console using Apex Programming Language.

---

# Conclusion
This practical demonstrates:
- Creation of Salesforce Developer Account
- Opening Developer Console
- Creating Apex Class
- Writing and Executing Apex Code
- Viewing Output using Debug Logs

This practical provides basic understanding of Apex programming in Salesforce.
