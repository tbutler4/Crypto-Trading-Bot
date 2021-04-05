# Crypto-Trading-Bot

## description:
**Crypto-Trading-Bot** is an application for users to trade or just keep updated with Tokens on the blockchain. My goal was to create a web application that allows users to watch trends with their favorite token, then buy or sell thier token. Users must register to the app to buy/sell. But the app is open for anyone to watch charts or make pretend trades.

## Wireframes
**main page**
<img src = "wireframes/WIREFRAME-1.png">
**logged in user dashboard**
<img src = "wireframes/WIREFRAME-2.png">
**logged in user purchase page**
<img src = "wireframes/WIREFRAME-3.png">
## User stories:
- As a user, I’m able to register to the web application
- As a user, I’m able to delete my account from the web application
- As a user, I’m able to log in to the web application
- As a user, I’m able to log out of the web application
- As a user, I’m able to purchase/sell tokens
- As a user, I’m able to add my trading info
- As a user, I’m able to watch all tokens

## Database models:

**A list of all the entities, its attributes and data types**
- Users: userId (PK, integer), userNname (varchar 255), userEmail (varchar 255), userPassword (varchar 255)=

**Business rules:**
- Candle data onn crypto token will show on home page but any other feature will be specific to each logged in user.
- Users data will be visible only to that user

**Entity relationship diagram:**

