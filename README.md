# Tic-Tac-Toe in C
### Video Demo:  https://youtu.be/GbNZpgHm3qc

### Description: 
For the final project I decided to develop in C a game very well known among children in Italy, I'm talking about "tris", known in English-speaking countries as tic-tac-toe.

### Technical description:
The program was developed in C in the only file present, tic-tac-toe.c, where we can find other functions in addition to the main:

- validSymbol: which checks that the inserted symbol is correct.
- clear: which clears the terminal of what was written.
- printNumberedGrid: which prints the numbered grid.
- printGrid: which prints the grid with the symbols entered by the players.
- checkWin: which at each turn checks if a player has won.
- play: the main function that calls all the functions described above, to manage the game.
  
### Game started:
At the start of the program a small introduction is made about the game and its purpose:

![image](https://user-images.githubusercontent.com/59999571/168448706-943b6cae-a127-4f54-9045-b3a64e25c57a.png)

Then the first player can enter his name and choose one of the two symbols, O or X.

![image](https://user-images.githubusercontent.com/59999571/168448018-2452b8b0-fc8e-4fe7-b8c0-18303861cdff.png)

There is an example if the player enter an invalid symbol:

![image](https://user-images.githubusercontent.com/59999571/168448010-a6e319af-2d98-4e3f-94e7-99323d494f7d.png)

Then the second player can enter his name and he will be automatically assigned the remaining symbol:

![image](https://user-images.githubusercontent.com/59999571/168448047-6d9c8446-c4d5-4fa9-aa4d-02d8a73dac26.png)

Before you start playing, you are reminded of how the grid works for inserting symbols:

![image](https://user-images.githubusercontent.com/59999571/168448092-12059ec8-d12f-4f7c-b57d-3e0a8db9e208.png)

One by one the players enter their symbol in the grid:

![image](https://user-images.githubusercontent.com/59999571/168448461-a8283328-8f37-4673-9c59-846f64d0aec3.png)

A mistake a player could make is to insert his symbol in an already occupied cell or in a range not between 1 and 9, but the program notices this and makes him choose the cell again:

![image](https://user-images.githubusercontent.com/59999571/168448494-75dc1cce-69a2-4d56-981c-5136f2254144.png)

The game ends in two cases: if a player puts three symbols in a row and wins or if the grid fills with no rows of three of the same symbols, then it is a tie:

![image](https://user-images.githubusercontent.com/59999571/168448591-b2de3bc8-5fa6-4818-8beb-9570fdc93a39.png)
![image](https://user-images.githubusercontent.com/59999571/168448613-ca7198ab-ad99-4ad6-9522-0810245388f5.png)

