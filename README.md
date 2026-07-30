# Calorie Counter

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)

## Short description

A calorie tracking app built with plain HTML, CSS, and JavaScript. You set a daily calorie budget, log meals and exercise, and it works out what's left for the day.

## Technologies

HTML5, CSS3, JavaScript (DOM manipulation, form handling)

## Features

- Set a daily calorie budget
- Add multiple entries for both meals and exercise
- Automatically calculates calories consumed, calories burned, and what remains
- Input validation with error messages for invalid entries
- A clear-form option to reset everything and start over

## The process

This was built without any framework, so the focus was on handling everything (adding dynamic entries, validating input, running the calculations) directly with the DOM API. Each meal or exercise entry needed to be added to the page on the fly and included in the running totals, so most of the logic centers on keeping the displayed entries and the underlying totals in sync as the user adds more of them.

## What I learned

- Manipulating the DOM directly to add and remove form entries dynamically
- Handling form submission and validating user input before running calculations
- Structuring vanilla JavaScript into small functions instead of one large script
- Giving clear feedback to the user (surplus vs. deficit) based on calculated values

## How it can be improved

- Save entries to local storage so they persist after a page refresh
- Add a simple chart or visual summary of calories over time
- Add a small predefined food database instead of manual entry only
- Improve the layout for smaller screens

## How to run the project

1. Clone the repo
2. Open `index.html` directly in your browser
