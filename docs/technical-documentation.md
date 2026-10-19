# Technical Documentation

## Project Overview

This project is an interactive personal portfolio website developed using HTML, CSS, and JavaScript.

Assignment 2 improves the original portfolio by adding dynamic content, form validation, user feedback, and simple animations.

## Technologies Used

- HTML: Used to create the structure and content of the website.
- CSS: Used for styling, responsive layout, project cards, and animations.
- JavaScript: Used for dynamic project details, form validation, user feedback, and the greeting feature.

## Project Structure

- `index.html` contains the main structure of the portfolio.
- `css/styles.css` contains the website styling and responsive design.
- `js/script.js` contains the interactive JavaScript features.
- `assets/images/` contains the project images.
- `docs/ai-usage-report.md` documents AI usage.
- `docs/technical-documentation.md` contains the technical documentation.

## Main Sections

### About Me

The About Me section introduces the portfolio owner and provides a short description of her interests.

### Projects

The Projects section displays portfolio projects using project cards.

Each project contains a Show Details button. When the user clicks the button, JavaScript displays additional information about that project. The button changes to Hide Details while the information is visible.

### Contact

The Contact section contains a form with:

- Name
- Email
- Message

JavaScript validates the form before showing a confirmation message.

## Dynamic Content

The website uses JavaScript to show and hide additional project information.

The Show Details button responds to a user click and changes the content displayed on the page.

## Form Validation

The contact form checks that:

- All fields contain information.
- The email follows a valid email format.

If the input is invalid, an error message is displayed.

If the input is valid, a success message is displayed and the form fields are cleared.

## User Feedback

The website provides clear feedback to the user.

Examples include:

- `Please fill in all fields.`
- `Please enter a valid email address.`
- `Thank you! Your message has been submitted.`

## Animation and Transitions

Project cards use a CSS hover transition.

When the user moves the pointer over a project card, the card moves slightly upward with a smooth transition.

## Responsive Design

The website uses Flexbox and CSS Grid.

A media query changes the layout on smaller screens.

On desktop screens, project cards appear in two columns.

On smaller screens, the project cards appear in one column and the navigation adjusts to fit the screen.

## JavaScript Greeting

The website gets the current hour using:

`new Date().getHours()`

It displays Good morning, Good afternoon, or Good evening depending on the current time.

## Testing

The website was tested by:

- Opening it in a web browser.
- Testing the Show Details and Hide Details buttons.
- Submitting the contact form with empty fields.
- Testing an invalid email address.
- Testing valid form input.
- Resizing the browser window to test the responsive layout.
- Testing the project card hover animation. 