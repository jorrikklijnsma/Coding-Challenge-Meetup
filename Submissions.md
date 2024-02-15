# Submitting your solutions?

## Introduction

You can submit your solutions by cloning this repository and sending the public repo link to the organizers. Here you can find more information on how to submit your solutions.

## The submission code format

Your submission needs to exist of plain JavaScript or CSS code. When the solution requires a HTML element, you need to add a HTML file as well. The HTML file should be named `index.html`. The JavaScript file should be named `solution.js` and the CSS file should be named `solution.css`. You can use the HTML template below to create your `index.html` file.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="solution.css">
  <title>Document</title>
</head>
<body>
  <script src="solution.js"></script>
</body>
</html>
```

## How to submit your solution?

### 1 Fork the repository

Fork the repository to your own GitHub account. You can do this by clicking the "Fork" button on the top right of the repository page.

### 2 Clone the repository

Clone the repository to your local machine. You can do this by running the following command in your terminal: (use your newly forked git URL)

```sh
git clone https://github.com/your-username/Coding-Challenge-Meetup.git
```

### 3 Create a new branch

Create a new branch for the current event. You can do this by running the following command in your terminal:

```sh
git checkout -b current-event-name
```

### 4 Solve the challenge

Solve the challenge in the `challenges` folder. You can find the challenges in the [JavaScript-Challenges.md](challenges/JavaScript-Challenges.md) and [CSS-Challenges.md](challenges/CSS-Challenges.md) files.

### 5 Submit your solution

Submit your solution by creating a new folder in the `submissions/css` or `submissions/javascript` folder. The folder name should be the name of the challenge you solved. (Including the heading index). For example: `submissions/javascript/5.2 Dice Roll Simulator`
Inside the challenge folder, add your solution file. The solution file should be named `solution.js` for JavaScript challenges and `solution.css` for CSS challenges.
Here is an file tree example of how your submission should look like:

```sh
submissions
├── css
│   └── 1.1\ Center\ an\ element
│       └── solution.css
└── javascript
    └── 5.2\ Dice\ Roll\ Simulator
        └── solution.js
```

### 6 Push your changes

Push your changes to your forked repository. You can do this by running the following command in your terminal:

```sh
git push origin current-event-name
```
