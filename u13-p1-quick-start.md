# 013 HTML Forms

## 🚀 Quick Start

To make a web form, you only need three things: the **container**, the **inputs**, and the **submit button**.

### 1. The Container (`<form>`)

Everything goes inside these tags.

```html
<form>

</form>

```

### 2. The Inputs (`<input>`)

This is where the user types in their information. The `type` attribute tells the browser what kind of form field to display.

* **Text:** `<input type="text">` (Standard box)
* **Email:** `<input type="email">` (Checks for the "@")

### 3. The Submit Button (`<button>`)

Without this, the user's data stays on the screen and goes nowhere.

```html
<button type="submit">Send It!</button>

```

---


## 🧠 Essential Concepts

If you want your form to actually work like a real form, remember this:

* **`label`**: Always wrap your label text in `<label>` tags. It makes the form accessible and tells the user what to type.
* **`placeholder`**: Use this to show a hint inside the form field before the user types in their info.
* *Example:* `<input placeholder="Enter your first name...">`


* **`required`**: Add this **attribute** to any input field to make it a required form field. If the user skips it, the browser will stop them automatically.

---

## 🛑 Troubleshooting 

**Did your form not work? Check for these common form mistakes:**

1. **No SUBMIT button?** Make sure you type your `<button>` element *before* the `</form>` tag.
2. **Email form field not validating?** Make sure you typed `type="email"`, not `type="mail"`.

---
