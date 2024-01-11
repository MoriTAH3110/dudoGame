# Dudo - web version of the dice game

## 1. What is Dudo? short version.   
Dudo (spanish for "I doubt") is a turn-based game of strategy, bluffing and probability where players try to guess how many occurrences of a number in a six-sided dice are currently on the table.

## 2. The game.
Dudo, or Perudo, is a dice game originated in South America, where players use an opaque cilinder to shake 5 six-sided dice and flip them onto the table so only they can see how each dice landed. Then, the first player will tell outloud how many instances of any number between 1 and 6, are currently in the table, taking into acount their own and other player dices.

The next player have two options to do in their turn:
- Raise the bid: Raise either the value or the occurrences of the previous bid.
- Challenge the bid: Calling the previous a lie will force all players to reveal what each roll.

After challenging the bid and revealing each players dice, the group will count the occurrences of the number called in the challenged bid. If the results are correct, the challenging player will lose a dice but if the bid was incorrect, the player who called it will lose a dice instead.

A lost dice will not play in the following round and the game is over where there is just one player with dice available.

## 3. Ruleset.
This is not an official nor the only ruleset for Dudo, it is the specific rules that will apply to the game version of this repo.

### Pre-game
- This is a two player game.
- Each player starts the game with 3 dices.
- Players will take turns to roll the dice and see their result, thus, the other player cannot look at the screen while the player in turn is checking their result.
- Players can check each of their results how many times necessary before hitting a start game button.

### Actual game
- When the game starts (after each player have check their reult and clicked on start game), the first player will only have the option to place a bid, stating which number and how many occurrences of it are in total.
- The following players will only have the option to raise the bid (raising the value of the number or the occurrences) or challenge the bid.

### Challenging the bid
- When challenging the bid, each player dice will be revealed and the game will count the occurrences of the number in the current bid.
- If the occurrences are equal to the bid, the challenging player will lose a dice.
- If the occurrences are not equal to the bid, the player who stated the bid will lose a dice.

### Game ending
- The game will end when one of the players lose all of their dice.
- The winner will be the player with dice still available

## 4. Dev Rules

This is a personal challenge/project, and there are specific conditions to be met during the development stage.

1. **Tools Available:**
   - This project must be implemented using pure HTML, CSS, and JavaScript. The use of libraries or frameworks is forbidden.

2. **Turn-Based Game:**
   - The game must follow a turn-based structure, where the project itself will count and manage the state of the game. Players are only required to place bids, challenge bids, and check their dice.

3. **Remote Connection:**
   - The challenge will not be considered complete until the game can be played in both public and private rooms with remote players.

4. **3D Graphics (Optional):**
   - While not mandatory, incorporating 3D meshes as part of the main game is a personal challenge. The 3D graphics will be implemented using Babylon JS as the engine and modeled in Blender.

