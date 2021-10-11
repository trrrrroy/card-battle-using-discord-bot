# card-battle-using-discord-bot
a pretty unoptimized discord js code for a discord bot

so uh i made this code for me and my friends' discord server

basically, the game is a turn-based card game where you can choose your deck with unique set of cards
and the goal of the game is to make your opponent's health reach 0

at the start of the game, both players have 6 energy, and it refills 5 energy after every turn

how to play:
1. anyone types in the command: >play
2. player 1 types: >play 1, to indicate that s/he is the first player
3. player 2 types: >play 2
4. player 1 chooses deck (>play A/B/C)
5. player 2 chooses deck (>play A/B/C)
6. player 1 chooses card (>play skillA/skillB/skillC/skillD) - each card has an attack value, shield value, special attribute, and energy cost
7. player 2 chooses card (>play skillA/skillB/skillC/skillD) - the shield value of player 2's card will block the attack of player 1's previous turn
8. anyone types the command: >, to continue the game (this is kind of an error but i don't have time to think of a way to fix it lol)
9. repeat steps 6-8 until a player reaches 0 health (a winner message will appear)
