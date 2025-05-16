````markdown
# JavaScript Trivia Bot 🤖

Welcome to the **JavaScript Trivia Bot** project — a fun, beginner-friendly coding exercise built using JavaScript!

## 📝 Project Description

The JavaScript Trivia Bot is a console-based bot that introduces itself, shares interesting facts about its favorite programming language, and ends with a friendly goodbye. It's a perfect project for learning how to:

- Declare variables
- Use string concatenation
- Log output to the console
- Reassign variables

## 📋 Features

- Greets the user upon startup
- Introduces itself with a name and location
- Shares three unique facts about its favorite language using variable reassignment
- Ends with a farewell message

## 🧠 Concepts Covered

- `var` and `let` for variable declarations
- String concatenation using the `+` operator
- Console logging with `console.log()`

## 💻 How to Run the Bot

1. Make sure you have Node.js installed (or use any JavaScript console).
2. Copy the code below into a file named `triviaBot.js`:

```javascript
// Greeting message
console.log("Hello! I'm your coding fun fact guide!");

// Bot's details
var botName = "Codey";
var botLocation = "Silicon Valley";
var favoriteLanguage = "JavaScript";

// Introduce the bot
console.log("My name is " + botName + " and I live on " + botLocation + ".");
console.log("My favorite programming language is " + favoriteLanguage + ".");

// Fun facts about the favorite language
let codingFact = favoriteLanguage + " was created in just 10 days!";
console.log(codingFact);

codingFact = favoriteLanguage + " can run both in the browser and on the server.";
console.log(codingFact);

codingFact = favoriteLanguage + " is one of the most popular programming languages in the world.";
console.log(codingFact);

// Farewell message
console.log("It was fun sharing these facts with you. Goodbye! - " + botName + " from " + botLocation + ".");
````

3. Run the file using Node.js:

```bash
node triviaBot.js
``

You should see all the messages appear in the console in order.

## 📚 Learning Outcome

This project reinforces core JavaScript skills through a hands-on mini script that mimics the flow of an interactive bot.

## 🚀 Author

Created by **Jordan Leturgez** as a JavaScript learning project.

---

Feel free to customize the bot's name, location, and facts to make it your own!

```
