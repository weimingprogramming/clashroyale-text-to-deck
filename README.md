To use:

Step 1: Open Webapp
web app accessible here: https://weimingprogramming.github.io/clashroyale-text-to-deck/

Step 2: Write out the cards you want/ Voice
"evo prince"
"hero musketeer"
"snowball" etc.

Step 3: The Webapp generates a link to RoyaleAPI with the exact deck. 

Step 4: Click copy deck on RoyaleAPI to copy the deck into Clash Royale automatically

Benefits:
- I can create a deck in Clash Royale just by listing down cards and I do not have to scroll.

**How this webapp was created**
How I added card information and pictures
I used RoyaleAPI to access all card information and include it in a JSON file (carddetails.json) which is read by index.html. 

What is the backend?
The entire app is contained in index.html and is in html. 

How does text matching work?
Reading of the text uses fuzzy matching using a simple levenshtein distance equation.
For more complex cards, I manually created over 100 nicknames
For example: when you write a nickname like "skarmy" or "jynxzi" it can identify the skeleton army or bowler card.

How do you do Speech Recognition?
I use window's inbuilt speech recognition plug in. I did not train it at all. Hence, the speech is not very accurate.

Why/How do you link to the RoyaleAPI website?
The only way for a deck to be copy-pastable to clashroyale directly is from the RoyaleAPI website. To create RoyaleAPI link, you need to understand how their links are generated, with each card being a small part of the total link.


