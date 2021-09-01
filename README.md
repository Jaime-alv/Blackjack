# Blackjack
A text-based blackjack game, with all features from classic blackjack for the whole family!

Everyone's favourite! The rules are simple, the play is thrilling and you can use all the strategies you want!
Nobody is going to be mad at you ;).
You can play with as many friends as you want!

Default and custom mode

You will be presented with an option to choose, play with the default game rules or your own custom ones.
Options are:
Minimun bet: represents the minimun bet each participant has to make at the start of each game
Funds: how much money each player have at available
Croupier show card: by default, croupier will show its first card, while second one is revealed when its turns begins.
By default:
Minimun bet: 5
Funds: 100
Croupier show one card

Number of players

After the rules are set, you'll be asked how many participants will be playing this session.
It affects how many packs of cards are.
You don't have to remember which number you are. The script will ask for your name and everytime it's your turn, it will use said name.
 

The Pack

The standard 52-card deck is used and, depending on the number of players, several decks could be shuffled together.
Yes, if there is only one deck, there will be only one Ace of Spades, as it should be!
The program will remember cards between games, if all Aces are gone, they're gone untill the game reshuffles decks.
When there are less than n number of cards left, it will be indicated with a prompt and it will be time for the cards to be reshuffled.

Object of the game

Each participant attempts to beat the dealer by getting a count as close to 21 as possible, without going over 21.

Card values/Scoring

Aces can be 1 or 11, when the player hit s (for stand), the game will pick the highest value without going over 21.
If a participant draws 'Ace of Spades' and 'Eight of Hearts', it will be displayed both values, 9 and 19; if, for example,
'five of Clubs' is drawn next, only 14 will be displayed, as 24 is over 21.
Face cards are 10 and any other card is its pip value.

Betting

Before the deal begins, each player places a bet. Minimun bet, by default, is 5, and maximun is the player's available money.

