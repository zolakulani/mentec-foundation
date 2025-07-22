# Chapter 5: Conditional Statements

## Learning Objectives
By the end of this chapter, you will:
- Understand what conditional statements are and how they control program flow
- Learn the syntax for if, else if, and else statements in JavaScript
- Apply conditionals to real-world decision-making scenarios
- Practice writing conditional code with guided exercises

---

## 5.1 What Are Conditional Statements?
Conditional statements let your program make decisions and execute code only when certain conditions are met. This is how you add logic and interactivity to your programs.

**Real-World Analogy:**  
Imagine you’re deciding what to wear:
- If it’s raining, you take an umbrella.
- Else if it’s sunny, you wear sunglasses.
- Otherwise, you dress normally.

This decision-making process is like conditional statements in programming.

---

## 5.2 Basic if Statement Syntax

```javascript
if (condition) {
  // code to run if condition is true
}
```

**Example:**
```javascript
let temperature = 30;
if (temperature > 25) {
  console.log("It's hot outside!");
}
```
If temperature is greater than 25, the message will be logged.

---

## 5.3 Using else and else if

These allow you to add more choices:

```javascript
if (temperature > 30) {
  console.log("It's very hot!");
} else if (temperature > 20) {
  console.log("The weather is nice.");
} else {
  console.log("It's a bit cold.");
}
```
The program checks conditions in order and runs the first true branch.

---

## 5.4 Comparison Operators

| Operator | Meaning                | Example      |
|----------|------------------------|-------------|
| ==       | Equal to               | x == 10     |
| ===      | Equal value & type     | x === 10    |
| !=       | Not equal              | x != 5      |
| <        | Less than              | x < 10      |
| >        | Greater than           | x > 5       |
| <=       | Less than or equal     | x <= 7      |
| >=       | Greater than or equal  | x >= 3      |

---

## 5.5 Logical Operators

| Operator | Meaning | Example             |
|----------|---------|---------------------|
| &&       | AND     | x > 5 && x < 10     |
| \|\|     | OR      | x < 5 \|\| x > 10   |
| !        | NOT     | !(x == 10)          |

---

## 5.6 Hands-On: Temperature Checker

```javascript
let temp = prompt("Enter the current temperature:");
if (temp > 30) {
  alert("It's very hot today!");
} else if (temp > 20) {
  alert("The weather is nice.");
} else {
  alert("It's a bit chilly.");
}
```
Run this in Replit and test different temperatures.

---

## 5.7 Check Your Understanding

- What does the else clause do?
- How does else if differ from if?
- What operator would you use to check if two values are exactly equal?
- How do logical AND (&&) and OR (||) differ?

---

## 5.8 Practice Exercises

1. Write a program that asks the user for their age and alerts whether they are a child (under 12), a teenager (12-18), or an adult (over 18).
2. Create a password checker that alerts “Access granted” if the password equals "letmein" and “Access denied” otherwise.
3. Combine conditions using && and || to check if a number is within or outside a range.

---

## Chapter Summary

- Conditional statements control which code runs based on conditions.
- Use if, else if, and else to add multiple branches.
- Comparison and logical operators help build complex conditions.
- Conditionals make your programs responsive and dynamic.

---

Here’s a step-by-step guide on how to use `git push` to upload your files to GitHub:

---

## 1. **Open a Terminal or Command Prompt**
- On Windows, you can use Command Prompt, PowerShell, or Git Bash.

## 2. **Navigate to Your Project Folder**
For example:
```sh
cd "C:\Users\shikw\OneDrive\Documents\mentec foundation\mentec foundation GitHub"
```

## 3. **Initialize Git (if you haven’t already)**
```sh
<code_block_to_apply_changes_from>
```

## 4. **Add Your Remote Repository**
If you haven’t connected your local folder to a GitHub repository yet, do this:
```sh
git remote add origin https://github.com/your-username/your-repo.git
```
Replace `your-username` and `your-repo` with your actual GitHub username and repository name.

## 5. **Add Your Files**
```sh
git add .
```
This stages all files in the folder for commit.

## 6. **Commit Your Changes**
```sh
git commit -m "Add chapter 5 and PDF"
```

## 7. **Push to GitHub**
If this is your first push, use:
```sh
git push -u origin main
```
or, if your default branch is called `master`:
```sh
git push -u origin master
```
For subsequent pushes, you can just use:
```sh
git push

```

---

### **Summary Table**

| Step | Command |
|------|---------|
| 1. Go to folder | `cd "your-folder-path"` |
| 2. Init git | `git init` |
| 3. Add remote | `git remote add origin <repo-url>` |
| 4. Add files | `git add .` |
| 5. Commit | `git commit -m "Your message"` |
| 6. Push | `git push -u origin main` |

---

**Let me know if you want a command you can copy-paste with your actual repo URL, or if you need help with any errors!**