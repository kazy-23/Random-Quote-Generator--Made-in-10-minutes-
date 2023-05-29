# Random Quote Generator (Made in 10 minutes)

This repository consists of a single index.html file that contains all the code.

HTML file shows random quotes for a quote API. I made this website in 10 minutes as a challange.

index.html:
- basic html 5 template.
- h1 tags that make up the title.
- p tag with id of "output" is where the javascript puts in the quote.
- i tag with id of "author" that is inside a p tag is where the javascript puts in the author of the quote.
- button tag with id of "generate" is what javascript listens to for starting quote generation.
- script tag listens when element with id of "generate" is clicked and then using fetch API gets quotes from a quote API, selects one of them and puts the text in the element with the id of "output" and the author in the element with the id of "author".
- style tag centers the whole website's text, adds some space between elements using margins and makes the buton taller and wider.
  
