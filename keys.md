% Key Commands for the Yu-gi-oh Mud

*note - you can switch between your edit box, which is where you type all your commands, and your "Output," where you can read your history, by holding down the control key and pushing Tab.
*note - the function key f11 will toggle between music and sound effects. the function key f12 will mute the various music or sound effects. function keys f9 and f10 will lower and raise volume respectavly.

*note - below shows the command followed by what the command does

Commands within the lobby

Language (language you want the Mud in) - Example: language spanish - using the command language followed by the language you speak will translate all cards into your desired language. the Mud defaults to english, but supports spanish, german, italian, and japanese

Who - tells you who is currently online

Finger (player name) - gives you win and loss statistics for that player

Create - creates a duel room in which you can wait or invite players to duel you

Join (player name) - joins the open duel room created by another player

Watch (player name) - places you in a spectator position to an all ready started duel so you can watch. *note, you can leave the spectator position by using the command: watch stop

deck publiclist - tell you all the public decks available to duel with. *note, publiclist is one word in this command

deck edit (name of deck) - example: deck edit dark magician - puts you into the deck editor specifically to make changes to that decks name. you can create a new deck by using deck edit (name your deck) and you will be launched into the deck editor with a completely empty deck which you named (name of your deck)

deck list - tells you a list of all your decks

deck view (name of deck) - tells you every card currently in that deck of that name

deck rename (current name of deck)=(new deck name) - example: deck rename dark magician=red-eyes black dragon - this command renames your exsisting deck to something else

deck copy (name of deck)=(name the deck)  - example: deck copy dark magician=dark magician 2 - this command makes an exact copy of the first labeled deck and puts the copy under the second name. *note, this command is used to copy public decks in order to make edits. if this is the case, you must use the name of who created the deck. example: deck copy josh/darkmagician=darkmagician. this will copy Josh's dark magician deck on the public list to your deck list under the same name. 

deck export (name of deck) - this command is used to give your deck a coding so that you can copy it from the output and paste it into another client. or other players may send you their deck in which you can paste there code into your edit box to copy their deck privatly. 

lookup (name of card) - using the lookup command followed by the name, or a fraction of the name of the card wil read you that specific card

afk - this command will label your username as afk, or away from keyboard to all other players. *note, using this command will toggle it on and off

Chat (message) - using the command chat followed by a message will communicate your message to everyone online. *note, you can disable the chat feature by using the command: chat all on its own. chat will toggle it on and off if you wish not to hear others chats. 

tell (player name) (message) - example: tell josh hello - this command is used to privatly communicate with a specific player. only you and that other player can see the message. *note, if a player has there chat disabled, the tell command is the only way to communicate with them. 

Commands in the duel room set up
*note - this is the location you are placed in after using the "create" command

finish - completes the duel room peramiders and opens the room to other players. *note, if you set the room to private you must invite other players to your room. 

leave - leaves the created duel room and returns you to the lobby

banlist (name of specific banlist) - example 1: banlist tcg - example 2: banlist none - this command allows you to choose which version of the banlist you want to play with. by using the command banlist tcg you are automatically using the most updated version of the banlist. *note, setting the banlist to none with the command: banlist none will allow you to play with banned cards in the modern Tcg. 

lifepoints 1 (number of lifepoints you want team 1 to start with) - example: lifepoints 1 5000 - this will switch team 1's starting life points to 5,000. *note, the official rules of yu-gi-oh have each player starting with 8,000 lifepoints, but you can switch it to any number. 

lifepoints 2 (number of life points you want team 2 to start with) - this command changes team 2's life points 

private - this command changes the duel room from public to private. once private, no other player can enter your room without an invitation. 

public - this command switches the duel room from private to public. in public mode all players can see your open room and can join without invitation. 

match - this command enables or disables match mode. when match mode is disabled it is a single duel. when match mode is enabled it is a best out of 3 contest. 

save - this command saves the settings or modifications to your duel room so that each time you create a duel room your specific settings or alterations are saved. *note, without using the save command will default you back to prior saved settings. 


Commands in open duel room
*note - this is the placement room after you use the "finish" command and before you start the duel

Start - this command will start the duel. *note, the duel will not start unless each player has loaded a deck and have moved into their respective teams. one player must be in team 1 and the other in team 2. also, only the player who created the room can use the start command

leave - this command will leave and abandon the current duel room and return you to the lobby

invite (player name) - example: invite josh - this will invite that specific player to your duel room. 

move 1 - moves you into team 1

move 2 - moves you into team 2

move 0 - moves you into neither team 1 or team 2 and puts you in a spectator position. *note, after the duel room has been created, after the "finish" command, you are in team 0 by default

deck (name of deck) - example: deck dark magician - loads your deck of that name. *note, if you are using a public deck you must include the player who created the deck. example: deck josh/dark magician. 

In Duel Commands 
*note - this is the placement/room that you are in after the "start" command
*note - before the duel begins  you must play rock, paper, sissors in order to determine who gets the choice to go first or second. 

1 - chooses rock
2 - chooses paper
3 - chooses sissors
*note - if you win, you will get the prompt: do you want to go first? 

y - this commands chooses yes to go first
n - this command chooses no, i do not want to go first

Dueling Commands
say (your message) - using say followed by your message will communicate to everyone currently in your duel room including spectators. *note, those players in the lobby will not see your message. 

h - tells you your hand

hand2 - tells you your opponent's hand

info h1 - will read card in the position 1 in your hand*note, you can use the same command to read each of your cards. examples: info h2 or info h4

h1 - this command will select the card located in your hand position 1. *note, using commands such as h1 or h3 or h5 will select their respective cards. 

*note - after you select a card with the "h1) command, you will be prompted with the following commands:
s - this will normal summon a monster in attack mode
m - this will normal summon a monster in deffense mode
c - this will special summon a monster if possible. *upon special summoning you will be prompted to choose a battle position. use 1 for face up attack position or 2 for face up deffense position
i - this will read out the information of the specific card you selected
v - will activate a spell or monster effect
t - will set the selected card face down in its fespective monster or spell/trap zone
z - will exit out of the selected card and return you back to starting position. 

tab - will read your side of the field. *note, spell out the word tab, t a b. this command is not to use the tab button

tab2 - will read opponent's side of the field. *note, tab2 is all one word with no spaces.

info m1 - will read the monster located in your 1 monster zone if one is there. *note, this same command can be used for all monster zones from m1 to m6. examples: info m3 or info m6

info om1 - will read opponent's monster located in their 1 monster zone. *note, same command can be used for all opponent's monster zones. *note, if opponent has monster in face down, no information will be read. only info given will be m1 facedown

info s1 - will read your spell or trap located in spell/trap zone 1. *note, this command can be used for each of the spell/trap zones from s1 to s6.

info os1 - will read opponent's spell/trap located in their spell/trap zone 1

extra - this command can be used to read through your extra deck monsters. *note, using info x1 will read the individual card located in the extra monster zone 1. the same command can be used for all 15 slots in your extra monster deck. 

grave - this will tell you all of your cards currently in your graveyard. *note, you can read individual cards by the command info g1 or infor g5 to read specific cards in those graveyard slots. the same can be done to read your opponent's grave yard with the command: info og1 or info og5 and so on. 

grave2 - tells you your opponent's grave yard and which cards are in it. 

remove - tells you the cards that are bannished face up in your bannish zone. *note, infor r1 will read you specific information on the banished card in the removed 1 slot. 

remove2 - will read you your opponent's bannished face up cards. *note, info or1 will read the specific card located in your opponent's removed 1 slot. 

b - this command will move your turn to battle phase. *note, this command can only be used after main phase 1. 

m - this command will move your turn to main phase 2. *note this can only be done after the battle phase. 
e - this command will move your turn to end phase thus ending your turn. *note, this command can be used at anytime during your turn. 

? - this command is used to give possible ideas to the player on which cards are activatable or which monsters can be summoned. *note, this command is very helpful to new players or players learning new decks. 

Reveal - this command will reveal your hand and extra deck to all spectators, but not to your opponent. *note, this command can be toggled on or off and is only active on a per duel bases. it is off by default at the start of every duel. this command is often used for learning purposes when experienced players help newer players. 

showhand - this command will show your hand to your opponent. *note, this is not a toggle and will only show your current hand one time. your opponent will not be able to see your hand again without another showhand command. also, showhand is one word for this command. 

cancel - this will ask your opponent to cancel the duel with no declared winner. *note, each player must use the command cancel to accept the cancelation of a duel. 

scoop - this will surrender to your opponent giving your opponent the victory and ending the duel. *note, while in a match, using scoop will only surrender a single duel within the "best of 3" duel match. only one player needs to use this command to end the duel unlike the cancel command. 

commands while in deck editor
*note - these commands are only used after using the "deck edit (name of deck)" command and while your in the deck editor

/ - moves you forward to the next card
? - moves you backwards to the prvious card

/(name of card) - example: /dark magicain - this will search for a specific card you named. *note, you can use fractions of a card name for example: /dark will search for any card with dark in its title. than you can use the / command to move forward through all the cards with dark in their title. 

s - while in deck editor, this will add the card you are on to your deck. *note, yu-gi-oh rules state that only 3 of each copy of a single card can be in your deck regaurdless if you put the ban list to none. 

r - while in deck editor, this will remove the specific card you are on from  your deck

l - while in deck editor, this will list the cards currently in your deck. 

/d:(card text) - example: /d:dark magician - using this command will search for text withih card descriptions and not title. the example: /d:dark magician will search for all cards with dark magician in there card description insted of their title. 

w - this will switch you from editing your main deck to editing your side deck. *note, you can use the w command while in deck editor to switch back and forth between main and side deck.

q - this will leave deck editor and return you to the lobby. 

*reminder - you can switch to your output, which shows your history, by holding the control key and pressing tab. you can then use the up and down arrows to re-read your history after using a command. example: info h1 to read my card in hand position 1. Then control + tab to output. Then up arrow to read card information line by line. than control +tab to return to edit field for next command. 
*note - using the out put to read cards can be helpful in slowing down information overload. reading cards in yu-gi-oh is very important since effects of cards can be different by just one word in its text. 
