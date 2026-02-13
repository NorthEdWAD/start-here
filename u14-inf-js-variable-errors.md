## **JS Variable Error Cheat Sheet**

### **1\. The "You Can’t Change Me\!" Error**

* **Error Message:** TypeError: Assignment to constant variable.  
* **What happened:** You tried to change the value of a variable that was declared with const.  
* **The Fix:** Change the keyword to let if the value needs to change, or stop trying to reassign it if it should stay the same.

### **2\. The "I Don't Know You" Error**

* **Error Message:** ReferenceError: \[variableName\] is not defined  
* **What happened:** You are trying to use a variable before you created it, or you misspelled the name (e.g., let score \= 10; but you typed console.log(scorre);).  
* **The Fix:** Check your spelling and make sure your let or const line comes *before* you try to use the variable.

### **3\. The "Tried to Clone Me" Error**

* **Error Message:** SyntaxError: Identifier '\[variableName\]' has already been declared  
* **What happened:** You tried to use let or const on the same name twice in the same scope (e.g., let weather \= "sunny"; followed by let weather \= "rainy";).  
* **The Fix:** Only use the keyword (let/const) the **first** time you create the variable. For updates, just use the name: weather \= "rainy";.

### **4\. The "Name Not Allowed" Error**

* **Error Message:** SyntaxError: Unexpected token or Invalid or unexpected token  
* **What happened:** You likely used a space in your variable name or started the name with a number (e.g., let user name or let 1stPlace).  
* **The Fix:** Use **camelCase** (e.g., userName) and always start names with a letter.

---

**Pro-Tip:** Always look at the **line number** on the right side of the error message in the console. It tells you exactly where JavaScript got confused\!

