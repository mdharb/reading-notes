# **JavaScript**

## **Error Handling & Debugging**

### **Order of Execution:**

* To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

### **Excution Contexts:**

* The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

* **Types of Excution Contexts:**
  - Global Contexts.
  - Function Contexts.
  - Eval Contexts. ***(Not Shown)***.

* **Variable Scope:** 
   - Global Scope.
   - Function-Level Scope.

### **The Stack:**

* JavaScript interpreter processes one line of a code at a time. When a statement needs data from another function it stacks a new function on top of the current task.

### **Each time a script enters a new execution context, there are two phases of activity:**

1. **Prepare:**
   - The new scope is created.
   - Variables, functions, and arguments are created. 
   - The value of the this keyword is determined.

2. **Execute**
   - Now it can assign values to variables 
   - Reference functions and run their code 
   - Execute statements

### **Error Objects:**

* Error objects can help you find where your mistakes are and browsers have tools to help you read them.

**Types of objects errors:**
  - Error.
  - Syntax Error.
  - Reference Error.
  - Eval Error.
  - URI Error.
  - Type Error.
  - Range Error.

### **DEAL WITH ERRORS:**

1. **DEBUG THE SCRIPT TO FIX ERRORS.**
   - Debugging is about deduction: eliminating potential causes of an error.

2. **HANDLE ERRORS GRACEFULLY.**
   - Try Statement.
   - Catch Statement.
   - Finally Statement.

### **Common Errors.**

* Go Back to Basic.
* Missed/ Extra Characters.
* Data Type Issues.

