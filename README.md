# Importance of *`this`*

## Instructions:

Return to your cards page: 

When a stream is clicked in the nav, that stream’s cards will transition and change background-color. When another stream is clicked, only that stream will transition and change background-color.

![completed page example picture](https://s3-eu-west-1.amazonaws.com/codeinstitute/fullstack/05-interactive-front-end-development/cardsPage.png)

## Hint:

This one is a bit trickier, but the idea is the same. Here give each list item in the navbar an individual id of stream1, stream2, and stream3. Each of our card elements will also have a class of stream1-card, stream2-card, or stream3-card. When we click on one of the list items in the navbar, we need to get the id of that list item using the *`this`* keyword. Once that has been achieved, use that value to target any elements that use that as a class name. 