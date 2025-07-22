# Chapter 6: Loops and Iteration

## Learning Objectives
By the end of this chapter, you will:
- Understand what loops are and why they are essential in programming
- Learn how to use for and while loops in JavaScript
- Write loops to automate repetitive tasks
- Practice coding exercises involving loops

---

## 6.1 What Are Loops?
Loops allow you to run the same block of code multiple times without rewriting it.

**Real-World Analogy:**
Imagine you need to send a birthday card to every member of your family. Instead of writing each card separately, you prepare one card and send it repeatedly — that’s what loops do for code.

---

## 6.2 The for Loop
The for loop runs a block of code a specific number of times.

**Syntax:**
```javascript
for (let i = 0; i < 5; i++) {
  console.log("Iteration number " + i);
}
```
- **Initialization:** `let i = 0` starts the counter
- **Condition:** `i < 5` runs the loop while true
- **Increment:** `i++` increases `i` by 1 after each loop

**Output:**
```
Iteration number 0
Iteration number 1
Iteration number 2
Iteration number 3
Iteration number 4
```

---

## 6.3 The while Loop
The while loop continues as long as a condition remains true.

**Syntax:**
```javascript
let count = 0;
while (count < 5) {
  console.log("Count is " + count);
  count++;
}
```

---

## 6.4 Loop Control Statements
- `break`: exits the loop early
- `continue`: skips the current iteration and moves to the next

---

## 6.5 Hands-On: Print Numbers
Write a loop to print numbers from 1 to 10.

```javascript
for (let num = 1; num <= 10; num++) {
  console.log(num);
}
```

---

## 6.6 Check Your Understanding
- What are the three parts of a for loop?
- How does a while loop differ from a for loop?
- What does the break statement do?
- When would you use continue? 