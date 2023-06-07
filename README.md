
# Quote Generator Project - JS
This code represents a Quote Generator web application written in HTML, CSS, and JavaScript. It fetches quotes from an external API and allows users to generate new quotes and share them on Twitter.

The code consists of the following components:

### 1. HTML structure:

- The `<head>` section contains the necessary metadata, including the character encoding, viewport configuration, and page title.
- External resources such as font icons and stylesheets are linked.
- The main HTML structure is defined within the `<body>` tag. It includes the quote container, loader, and script.
### 2. CSS styles:

CSS styles are embedded within the style.css file. These styles define the appearance and layout of the elements in the quote generator.
### 3. Quote Container:

The quote container is a `<div>` element with the class `"quote-container"` and the id `"quote-container"`. It holds the quote text, author, and buttons.
### 4. Quote Text and Author:

The quote text and author are displayed within separate `<div>` elements with the classes `"quote-text"` and `"quote-author"`, respectively. They are populated dynamically based on the fetched quote data.
### 5. Buttons:

Two buttons are provided:
- The Twitter button, identified by the class `"twitter-button"` and the id `"twitter"`, allows users to tweet the displayed quote and author.
- The "New Quote" button, identified by the id `"new-quote"`, triggers the generation of a new quote when clicked.
### 6. Loader:

The loader is represented by a `<div>` element with the class `"loader"` and the id `"loader"`. It is initially displayed while quotes are being fetched, and hidden once the process is complete.
### 7. JavaScript functionality:

- The JavaScript code is enclosed within the <script> tags at the end of the HTML body.
- The DOM elements are stored in variables using `document.getElementById`.
- Functions are defined to handle the loading state, displaying a new quote, fetching quotes from the API, and tweeting the current quote.
- Event listeners are set up for the `"New Quote"` and `"Tweet This"` buttons.
- On page load, the getQuotes function is called to fetch the initial set of quotes. <p>
That concludes the documentation for the provided code. 
