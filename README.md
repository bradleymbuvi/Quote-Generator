# Quote-Generator

Introduction

Are you looking for a daily dose of inspiration or a quote that truly encapsulates your feelings?
From wisdom, love, success and perseverance, I aim to build a Single Page Application (SPA) that offers a variety of quotes from renowned thinkers, authors and philosophers.
With each click, you will encounter a new gem of wisdom to uplift your spirits and ignite your imagination.

Project Requirements

1. Your app must be a HTML/CSS/JS/Bootstrap or Tailwind frontend that accesses data from a public API. All interactions between the client and the API should be handled asynchronously and use JSON as the communication format.

2. Your entire app must run on a single page. There should be NO redirects. In other words, your project will contain a single HTML file.

3. Your app needs to incorporate at least 3 separate event listeners (DOMContentLoaded, click, change, submit, etc.).

4. Some interactivity is required. This could be as simple as adding a "like" button or adding comments. These interactions do not need to persist after reloading the page.

5. Follow good coding practices. Keep your code DRY (Do not repeat yourself) by utilizing functions to abstract repetitive code.

Solutions
1. The app provides users with random selection of inspiring and motivational quotes
2. A user simply clicks “New Quote” button with each click offering a new random quote
3. It allows the user to share the quote that resonates with him/her on social media
4. Integrate speech
5. Free for all users


Core Feature

The Quote Generator uses an API (Application Programming Interface) to fetch quotes from a database of famous quotes. The API is connected to a server that receives requests from users who want to access the quotes. When a user clicks on the “New Quote” button, the server sends a request to the API, which returns a random quote from its database. The quote is then displayed on the user’s screen, along with the name of the author.


The API data used is https://api.quotable.io
