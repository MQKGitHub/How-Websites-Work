## 🛡️ How Websites Work

**Room:** [How Websites Work — TryHackMe](https://tryhackme.com/room/howwebsiteswork)  
**Status:** ✅ Completed  
**Date:** 23 April 2025

### 🎯 Objective
This room introduced how websites function from both the front and back end. The goal was to understand how browsers communicate with servers, how HTML, CSS, and JavaScript come together to build pages, and how poor coding practices can expose vulnerabilities like HTML injection or sensitive data leakage.

---

### 🗝️ Key Concepts  
- Front-end vs back-end – The front end is what users see in their browser; the back end processes requests and sends responses.  
- HTML structure – Websites are built using tags like `<html>`, `<head>`, `<body>`, and various elements to create content.  
- JavaScript – Adds interactivity by responding to events and modifying the page content dynamically.  
- Sensitive data exposure – Poorly protected frontend code can reveal credentials or internal links.  
- HTML injection – A vulnerability where unsanitised user input is displayed as HTML, allowing attackers to alter page content.  
- Input sanitisation – Essential to prevent attackers from injecting code into web applications.  

---

### 🛠️ Tools Used
- Browser DevTools — Used to inspect HTML structure and view source code.
- TryHackMe’s virtual environment — Used to interact with the target website and test vulnerabilities.

---

### ⚠️ Challenges Faced
- At first, I struggled to grasp how JavaScript interacts with HTML elements to change content on the page.  
- Playing around with the browser’s DevTools and seeing real-time changes helped me understand better.  
- Also took a moment to understand the difference between visible content and hidden source code, especially when it comes to exposed data.

---

### 🧠 What I Learned
- Learned the basic structure of how websites are built using HTML, CSS, and JavaScript.  
- Understood how browsers and web servers communicate through requests and responses.  
- Found out how insecure coding (like leaving credentials in HTML) can lead to real security risks.

---

### 🌐 Real-World Application:
> Developers and pentesters need to check source code for exposed secrets or hidden links. Frontend inspection is one of the quickest ways to spot potential issues before diving deeper.

---

### 💭 Reflections:
- It was eye-opening to see how even beginner-level web pages can have serious vulnerabilities.  
- I enjoyed experimenting with JavaScript snippets and seeing how they update the DOM.  
