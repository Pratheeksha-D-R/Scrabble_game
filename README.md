# Scrabble_game
Simple scrabble game in C

HOW TO RUN????
--->download all the files and keep them in same folder.
--->run scrabble code.c 
--->play the game and enjoy!!!

//////////////////////////////////////////////////////////////////////////////////////

letters1.csv contains the index, ASCII value, number of tiles and score of that letter.

///////////////////////////////////////////////////////////////////////////////////////

words2.txt contains all possible words that can be made in scrabble game.

///////////////////////////////////////////////////////////////////////////////////////

tnode is a binary tree with nodes being the words player forms.

createNode() --> creates new node for the word formed by player.

insert_tree() --> inserts newnode formed into the binary tree at its respective position maintaing the binary tree constraints.

search_tree() --> checks whether the new word entered is already formed before by traversing through the binary tree.

check() --> checks whether the word entered by the player is valid or not by traversing through the words in words2.txt.

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

node is a structure which contains details of the index of letter,letter,count of letter,score of letter and a pointer which points to the next letter.
 
create_list() --> creates list containing details present in letters1.csv

random(x)  --> randomly generates x number of letters from the heap of tiles

traversal() -->checks whether randomly generated letter is present in the heap if tiles ;if present it will decrement the count of that letter; if not it will return zero. 

search_score() --> gets the score of the letter passed.

insert() --> adds randomly generated letter to the 10tiles that the player should use to form words.

check_letter()  --> checks whether letters of the word entered by the player are present in randomly generated letters.

get_letters()  --> replaces the letters used to make new word with new letters by randomly picking letters from heap of tiles.

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


create_table() --> creates scrabble board

display_table() --> displays the scrabble board

display()  --> displays scores of players and randomly generated 10 letters that can be used to form new words.

///////////////////////////////////////////////////////////////////////////////////////////////////////////////

search_places_hor() -->searches if the letters entered by the user can be placed on the board after seeing the words around the index mentioned horizontally .

search_places_ver() -->searches if the letters entered by the user can be placed on the board after seeing the words around the index mentioned vertically. 

play() --> takes inputs from player (eg: wheter to form word horizontally or vertically , on which column and row etc.) 

change() --> generates new set of random letters when no words can be formed by using present set of letters.


/////////////////////////////////////////////////////////////////////////////////////////////////////////////

P.S. It is more like scrabble game except the fact that both players can form words using the same set of randomly generated tiles , whereas in real game one player is not supposed to see other players letters.

--> If anyone is planning to do as your data structures project you can use teamviewer or any other means to connect pcs/laptops together ,two players can play the game happily!!!!!

