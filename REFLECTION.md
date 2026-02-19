# Relections on Learning
**1. Summarize your understanding of `node_modules` and it's relationship with `package.json` (covered in the video for the lesson).**
 - package.json is the file that lists the project’s dependencies and project information.
When you run npm install, Node reads package.json and downloads those dependencies into the node_modules folder.

**2. What does the ${} syntax do inside backticks? Why is it useful?**
 - ${} is used inside template literals (backticks ` `) to insert variables or expressions into a string.
It’s useful because it makes combining text and variables easier and more readable.

**3. What happened when you saved your code in VS Code? (Did it auto-format? Did you see any errors?)**
 - When saving, VS Code executed the save with no issues or auto formatting as syntax was already correct. There were no errors.
 - I do understand what could happen especially since I have Prettier installed. But if there were errors after saving, it would have shown them or warnings. 
  
**4. How many commits did you make for this assignment? Why is it better to make multiple small commits instead of one large commit?**
 - For this assignment, I made 3 commits. Two commits were index.js and one commit was reflection.md
 - It is better to make small commits to be able to track changes easier, rollback steps to fix mistakes, and show progress.

**5. When do we use `const` vs `let`? What about `var`?**
 - const: is used when the value will not be reassigned
 - let: is used when the value needs to change later
 - var: old way to declare variables and should be avoided due to scope behavior
