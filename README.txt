

Portfolio Website Explanation

1. What Each HTML Element Does:

- <!DOCTYPE html>: Declares the document type and HTML version (HTML5).
- <html>: Root element that wraps all the content on the page.
- <head>: Contains metadata like title, character encoding, and favicon.
- <title>: Sets the title shown on the browser tab.
- <meta charset="UTF-8">: Defines the character encoding for proper text display.
- <link>: Links to an external resource, here used for the favicon image.
- <body>: Holds all the visible content of the webpage.

Inside <body>:
- <header>: Defines the top section, usually for navigation or branding.
- <h1>, <h2>, <h3>, <h4>: Headings used to organize content hierarchically.
- <nav>: Contains links for navigating across pages.
- <ul> / <ol>: Unordered and ordered lists (used for skills and education).
- <li>: List item inside ul or ol.
- <section>: Used to separate content into meaningful parts like "About", "Projects".
- <p>: Paragraphs for text content.
- <a>: Anchor tag for hyperlinks (e.g., to LinkedIn, other pages).
- <table>, <thead>, <tbody>, <tr>, <td>, <th>: Used to display project data in a tabular format.
- <form>: Defines a form for user input (used in contact page).
- <input>: Takes user input (text, email, date, range, etc.).
- <textarea>: Multi-line text input.
- <select> and <option>: Drop-down for choosing a service.
- <footer>: Contains contact details and page-end content.

2. Why Specific Input Types Were Chosen:

In the contact form (contact.html):
- type="text": For user names (free text).
- type="email": Validates proper email format automatically.
- type="tel": Designed to accept phone numbers (with pattern validation).
- type="date": Allows users to select a preferred date from a calendar.
- type="range": Used to rate the website from 1 to 10 visually.
- type="checkbox": Lets users choose multiple preferred contact methods.
- type="radio": Restricts the user to select only one type of inquiry.
- select and option: Used for choosing services from predefined options.

These types improve form validation, user experience, and data clarity.

3. How the Navigation Structure Works (with all HTML elements explained):

Across all pages:
- A <nav> element (in portfolio.html and about.html) contains links (<a>) to other pages like:
  - Home (portfolio.html)
  - About Me (about.html)
  - Contact (contact.html)
- In about.html, navigation is internal too, using #contact to scroll to the footer section.
- Nested <ul> and <li> are used in the main portfolio's navigation to create dropdown-style navigation under "Pages".
- Each page is consistent in structure with <header> for titles, <main> for content, and <footer> for extra info or links back to the portfolio.
