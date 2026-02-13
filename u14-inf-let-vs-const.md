## 

**let** vs **const** in Modern JavaScript

| Keyword | Explanation (Imagine a box) |
| :---- | :---- |
| let | Think of **let** as a labelled box.  You can place a value inside (assign it during declaration), and later you can take out the old value and replace it with a new one (reassignment). |

```javascript
let age = 16; // Assigning the value 16 to the box labeled "age"console.log(age); // Output: 16age = 18; // Taking out the old value (16) and replacing it with 18console.log(age); // Output: 18
```

**const** 

* Imagine **const** like a locked box with a value inside  
* You set the value when you create the box (during declaration), and that value is locked in forever  
* You can't take the value out of the box or replace it with something else (reassignment)  
* You cannot change the value stored in the box

```javascript
const PI = 3.14; // Setting the value of PI (in a locked box) to 3.14console.log(PI); // Output: 3.14PI = 22/7; // This will generate an error because you can't change the value in a const (locked) boxconsole.log(PI); // This line of code won't execute (run) because of the error
```

Key points to remember about the keywords **let** and **const**:

* Use **let** when you need a variable that can change its value throughout your code

* Use **const** when you have a fixed value that shouldn't be changed, like mathematical constants (PI) or configuration settings

* **const** makes your code more predictable and helps prevent accidental changes to your code

**Bonus tip:** Get in the habit of using **const** by default and only switch to **let** when you specifically need to overwrite or replace the value currently assigned to a variable.