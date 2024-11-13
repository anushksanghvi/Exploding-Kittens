<h1 align="center">Exploding Kittens</h1>

<p align="center">
This will be an online single-player card game that consists of 4 different types of cards

- Cat card 😼
- Defuse card 🙅‍♂️
- Shuffle card 🔀
- Exploding kitten card 💣

There will be a button to start the game. When the game is started there will be a deck of 5 cards ordered randomly. Each time user clicks on the deck a card is revealed and that card is removed from the deck. A player wins the game once he draws all 5 cards from the deck and there is no card left to draw.
</p>

## Rules
- If the card drawn from the deck is a cat card, then the card is removed from the deck.
- If the card is exploding kitten (bomb) then the player loses the game.
- If the card is defusing card, then the card is removed from the deck. This card can be used to defuse one bomb that may come in subsequent cards drawn from the deck.
- If the card is a shuffle card, then the game is restarted and the deck is filled with 5 cards again.

<br />

## Getting Started

### Prerequisites

- NPM 
- Node JS
- MongoDB

### Setup


The project repository can be found in [GitHub link](https://github.com/anushksanghvi/Exploding-Kittens.git) or just clone the project using this command. 


```
Using HTTPS

# git clone  https://github.com/anushksanghvi/Exploding-Kittens.git
```

## Install

Install NPM

Check that you have node and npm installed

To check if you have Node.js installed, run this command in your terminal:


```
node -v
```

To confirm that you have npm installed you can run this command in your terminal:


```
npm -v
```


To install all the dependences of the project, run the following command:


```
npm install
```


To run the application got to the client folder and run the following command:

```
npm start
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file in server folder

`MONGO_URL`

`PORT`



### Tools used on this project

- Visual Studio Code
- MongoDB compass

<br/>

