# Hearthstone-Game

## Description

This project is a fully functional implementation of the popular game "Hearthstone: Heroes of Warcraft" using Java. It follows the Model-Controller-View architectural pattern and serves as an exercise in object-oriented programming (OOP). The game features the following main components:

1. **Heroes**: There are a total of 5 heroes to choose from at the beginning of the game.

2. **Minions**: These are the playable cards in the game, controlled by the player who summoned them. Minions can be commanded to attack the opponent's minions or the opposing hero.

## Language and GUI

- The game is implemented in Java.
- It uses Java Swing for the graphical user interface (GUI).

## Getting Started

To run the game, follow these instructions:

1. Import the project into your preferred Integrated Development Environment (IDE).

2. Open the `Controller` class.

3. Run the `Controller` class to start the game.

## Game Instructions

1. **Selecting Heroes**:
   - When you open the game, you will see 5 heroes displayed as buttons on the screen.
   - Select the first hero by clicking on their button.
   - Select the second hero in the same way, and the game will start.

2. **Playing Minions**:
   - To play a minion card from your hand, click on the minion.
   - A zoom panel will display the card properties for clarity.
   - If you decide to play the minion, click on the zoom panel itself.
   - Otherwise, click on any other button to cancel.

3. **Casting Spells**:
   - To cast a spell card from your hand, click on the spell.
   - A zoom panel will display the card properties.
   - If the spell requires a target, a message saying "choose the target" will be displayed.
   - Click on the target (minion or hero) to apply the spell's effect.
   - For spells without a target, clicking on the zoom panel will activate the spell.
   - Click any other button to cancel.

4. **Minion Attacks**:
   - To attack with a minion on your field, click on the minion.
   - Follow the instructions to choose the target for the attack.
   - You will see the effects of the attack on both the attacker and the target.

5. **Ending Your Turn**:
   - Click the yellow "End Turn" button on the right of the screen to end your turn.

6. **Screen Orientation**:
   - The current hero's hand and field are fixed at the bottom half of the screen.
   - The opponent's field is displayed at the top half.
   - The opponent's hand is not shown.
   - Once you end your turn, the opponent becomes the current hero, and their hand and field are displayed at the bottom.

7. **Zoom Panel**:
   - The properties of cards in your hand may not be clear initially.
   - A zoom panel is available to display card details when you click on a card before playing it.
   - If you decide to play the card, click on the zoom panel itself.

8. **Hero Power**:
   - To use the hero's power, click on the hero power image.
   - If the hero power requires a target, click on the minion or hero you want to target.
   - You will see the effect of the hero power.

Enjoy playing Hearthstone!

## Screenshots (Game Preview)

![HearthStone 1](https://github.com/Ziaad-Khaled/hearthstone-game/assets/77291238/b7d98017-8f54-4bb0-8051-a4975cb622ef)
![HearthStone 2](https://github.com/Ziaad-Khaled/hearthstone-game/assets/77291238/2695eb86-d0b2-484b-92fe-c86626d1e9c1)

