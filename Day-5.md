# Web Debugging and Optimization Exercise

## Overview

This exercise is designed to improve your skills in web debugging and optimization. You will be working with an intentionally flawed web application. Your task is to identify and document the problems in the provided HTML, CSS, and JavaScript files.

## Instructions

Copy this README.md into your Devtools REPO in a new MD file called Day-5.md

### Step 1: Identify Problems

Go through the provided files (`index.html`, `style.css`, and `app.js`). Each file contains several marked problems (indicated by comments like `<!-- Problem 1: -->`, `/* Problem 5: */`, etc.). Your task is to identify what each problem is and why it is an issue.

### Step 2: Document Each Problem

In this README.md file, document each problem. Write a sentence for each problem explaining what the issue is and why it's problematic. Use the format below for your documentation:

#### Problem 1:

- Description: [Does not have a <meta name="viewport"> tag with width or initial-scaleNo `<meta name="viewport">` tag found, document doesn't have a <title> element, and document does not have a meta description]

#### Problem 2:

- Description: [Image Alt Attribute Empty]

### Problem 3:

- Description: [jQuery Version]

### Problem 4:

- Description: [Don't see problem 4]

### Problem 5:

- Description: [Overuse of !important]

### Problem 6:

- Description: [Unused Classes]

### Problem 7:

- Description: [Image Size]

### Problem 8:

- Description: [Descendant Selector Specificity]

### Problem 9:

- Description: [Asynchronous Code]

### Problem 10:

- Description: [ Blocking Operation]

### Problem 11:

- Description: [jQuery Usage]

### Step 3: Propose Solutions

For each identified problem, propose a solution or an optimization strategy. Briefly describe how you would fix the issue.

#### Problem 1:

- Solution: [It's a good practice to include the character set for proper rendering. and add meta and title]

#### Problem 2:

- Solution: [While the alt attribute is present for the <img> tag, it's empty. It's recommended to provide a descriptive text for the alt attribute to improve accessibility.]

#### Problem 3:

- Solution:[The code includes jQuery from a CDN with version 3.5.1. Depending on your requirements, you might want to check if there is a more recent version available and update the link accordingly.]

#### Problem 4:

- Solution:[]

#### Problem 5:

- Solution:[The use of !important is generally discouraged as it can make your styles harder to manage and override. In this case, it's used for various properties in the body selector. It's recommended to avoid unnecessary use of !important unless absolutely necessary]

#### Problem 6

- Solution:[The classes .unused-class-1, .unused-class-2, and .unused-class-3 are defined but not used in the provided HTML. If these classes are not being used, it's better to remove them to keep the code clean.]

#### Problem 7:

- Solution:[Setting a fixed width of 1200px for the image with img#largeImage might cause issues with responsiveness. It's generally better to use relative units or percentages to allow for better adaptability to different screen sizes. For example]

#### Problem 8:

- Solution:[The selector body div#profileContainer > h2 has high specificity, and it might not be necessary. You can simplify it to just #profileContainer h2 if there are no conflicting styles elsewhere]

#### Problem 9:

- Solution:[The code appears to be part of an asynchronous operation, possibly fetching data and updating the DOM. However, it's missing the context of how and where the profileContainer is defined. Ensure that you have a valid reference to the DOM element with the id profileContainer before trying to append paragraphs to it.
Example (assuming profileContainer is an HTML element with id profileContainer):]

#### Problem 10:

- Solution:[The loop that calculates the sum of numbers from 0 to 99999 is a blocking operation. This might lead to performance issues, especially in web applications, as it can freeze the UI during the loop execution. Consider using asynchronous operations or web workers for long-running tasks to avoid blocking the main thread.]


#### Problem 11:

- Solution:[The code uses jQuery to append a paragraph to the body. If you're already using vanilla JavaScript for other parts of the code, consider using it consistently. If you want to stick with jQuery, ensure that the jQuery library is properly included before using it.
Example using vanilla JavaScript:]

### Step 4: Reflect

I learned more about using lighthouse.

