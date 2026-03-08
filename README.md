# UNO Gaming Hub

## Project Overview

UNO Gaming Hub is a web-based interface for the classic UNO card game.
The project focuses on building an interactive sample game environment using **HTML and CSS**, including animated cards, deck interactions, and multiple interface pages.

The site includes a home page, game lobby, deck table interface, and rules page.

---

# Setup Instructions

1. Clone or download the repository.
2. Ensure all files remain in the same directory structure.
3. Open `index.html` in a web browser to start the application.
4. IMPORTANT - This project is specifically designed to run on GSU's CODD server! Although it has been tested in other browsers, it is best experienced on desktop in firefox/chrome!

No additional installation or frameworks are required.

---

# Project Structure

```
UNO-Gaming-Hub
│
├── Assets/
│   └── (UNO card images and symbols used throughout the project)
│
├── index.html
├── index_style.css
│
├── deck-table.html
├── deck-table.css
│
├── game-lobby.html
├── lobby.css
│
├── rules.html
|__ rules.css
```


*** Homepage (Page 1, “UNO Gaming Hub” )opens with beginning animation and provides a brief overview of UNO and links to the game lobby, deck table, and rules. This page serves as the main lobby that players will begin at and return to after a game. The page layout uses flexbox to center the hero section both vertically and horizontally, ensuring it remains prominent on all screen sizes. The hero section includes the title, splash text about the game of UNO, and clear, styled buttons to every other page of the UNO game site. In the background, there is a CSS animated background of floating, rotating uno cards. This animation utilizes CSS keyframe animations to rotate and move from left to right, creating a fun enviorment for this landing page. The initial fade-in animation and button hover effects also add polish and visual interest to this page.

*** Game lobby(Page 2, “UNO Lobby - Waiting…” ) contains a waiting page to join the game, displaying waiting time, available game lobbies, and online friends. This page also links to the deck table so that the user can check their available decks. 

*** Deck table (Page 3, “UNO Deck Table” )displays a sample deck and example play area for users to practice in, complete with deck stacks and accompanying animations. Users are able to view their own hand, view the current cards to draw, and view discarded cards. This page utilizes a grid layout for the main table and absolute positioning for overlapping card stacks, which allows for cards to be placed in decks and stack realistically. The top discard and draw cards are flippable using a CSS transform on hover, while the cards underneath both use a CSS spread animation for viewing upon being hovered over. The player hand cards are displayed in a fan layout using CSS vairables to replicate real card playing games, and cards in the player's hand glow and lift slightly to indicate which card is being hovered over. The player's hand cards are hand-styled using pseudo-elements and styled containers to replicate UNO cards and show clear card hierarchy and value. 

*** Rules (Page 4, “UNO - Rules and Tips” ) page contains basic rules for the game, as well as detailed explanations of each card with flip animations for each one. There is also a strategy section with few pointers and tips for playing. 
