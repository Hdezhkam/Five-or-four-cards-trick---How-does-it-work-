# A-five-or-Four-cards-trick---How-does-it-work-
solution for A five (or Four) cards puzzle 

In this puzzle we should encode 2 main keys:

 1- Number (value) of selected card.
 
 2- Type of selected Card (Heart, Spades, Diamond or Clubs)

A-Start of the game

Player-1 takes a card from 52 cards and shows it to player-2. Player-2 should encode selected card by 4 cards that player-1 gives to player-2 arbitrarily from 52 cards.

B-Encoding the selected card 
Step 1: Player-2 demonstrates the number of the selected card by using Binary Numbers System, Player-2 can make this number by putting cards on the back (with the value of 0) and on top (with the value of 1)  :
 0001 -->(Ace), (back, back, back, on)
 0010 -->2, (back, back, on, back)
 0011 -->3,
 0100 -->4,
.
.
1011--> (jack),
1100--> (queen),
1101--> (king)
Binary Numbers System: https://www.mathsisfun.com/binary-number-system.html

Step 2: Player-2 demonstrates type of the card based on one of the below scenarios:
Note1: Player-2 and Player-3 set a rule for the arrangement of the cards and determine 4 positions based on the below example:
[P1 ♠, P2 ♣, P3 ♥, P4 ♦]

Scenario A) 4 different kinds of cards: (♠, ♣, ♥, ♦)
Player-2 puts the selected type at the first position. (Positioning is from right to left)

Scenario B) 2 different and 2 of a kind: (♠, ♠, ♥, ♦)

1-if the selected card is same as the similar pair: (♠, ♠)
- Player-2 puts the similar pair at the first position. (♥, ♦, small ♠, large ♠)
2-if the selected card is same as one of the 2 different cards: (♥ or ♦)
- Player-2 puts selected type at the first position (♠, ♠, ♥ or ♦)
3-If the selected card is not included in the cards. (♣)
- Player-2 puts the similar pair at the first positions but in large to small order. (♥, ♦, large ♠, small ♠)

Scenario C) 3 of a kind and 1 different (♠, ♠, ♠, ♦)
1-If the selected card is similar to the 3 of a kind: (♠)
- Player-2 puts 3 similar cards at the first position. (♦, ♠, ♠, ♠)
2-If the selected card is similar to the different one: (♦)
- Player-2 puts 3 similar cards at the end in small to large order and put the 4th card at the first position. (♠, ♠, ♠,♦)
3- If the selected card is not included in the cards: (♣ or ♥)
- Player-2 puts the different card (♦) at the position of that kind of card acceding to the basic arranged rule [P1 ♠, P2 ♣, P3 ♥, P4 ♦]-ex: selected card is (♣)  [♠, ♦, ♠, ♠]

Scenario D) 2 pairs of similar kind (♠, ♠, ♥, ♥)
1-If the selected card is same as each pair: (♠ or ♥)
- Player-2 puts the similar pair at the first position in small to large order.
2- If the selected card is not included in the cards: (♦ or ♣)
- Player-2 puts the pairs from right hand in disordering status (which is considered as a sign for player-3 that the selected kind is not among the cards. On the other hand player-2 puts the highest card (type and number) at the position of that kind of card acceding to the basic arranged rule. 
[P1 ♠, P2 ♣, P3 ♥, P4 ♦].

