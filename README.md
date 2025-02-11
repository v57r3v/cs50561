java c
Algorithms and   Data Structures   I
Lab 5:   Stackjack
Background
The card game Blackjack   is   played all across the world.   Blackjack uses   a   standard   52   playing   card   deck.   There   are   many variations on   rules,   but for this   Lab   here are the ones you will   need to   know:
-            A hand consists   of a   stack   of cards.
-             Each card   has a   respective   point value:
-             Numeric cards (2 -   10) are worth that   many   points   (e.g.   a   5   is   worth   5   points)
-             Face cards Jack, Queen, and   King   are worth   10   points
-            Aces can   be worth either   1   or   11   points
-          A   hand’s   score   is   the   sum   of   each   of   its   cards’   point   values
-            The   Player plays against   a   Dealer
-            Whoever gets closest to 21 without going over wins
-             In the event of   a   tie,   the   Dealer wins
Exercise
First, download the starter code from this folder. The starter code   includes the following files:
-             Lab5.java:   Driver program.   Use   it to compare your output to the   output   shown   here.
-            StackInterface.java: An interface for the Stack ADT
-             HandScorerInterface.java: An interface that has one   method:
-          public   int   score(Stack   hand)
-          LinkedStack.java: A complete   implementation   of   Stack   Interface   that   uses   a   linked   chain/list
-          Card.java: A   Card   class.   Has   methods   for   retrieving   the   suit   (hearts,   spades,   clubs,   diamonds)   and   value   (“2”   , “3”   , “4”   ,  代 写Algorithms and Data Structures I Lab 5: StackjackJava
代做程序编程语言 .   .   .”jack”   , “queen”   ,   “king”   ,   “ace”)
Second, take a look at the HandScorerInterface   .java   file. You will be responsible for following the comments in the interface file and implementing the   score   method   in the   HandScorer   class.   Here   are   some   example hands and   their   scores:
Hand
Score
10, jack, ace
21
jack, queen,   8
28
ace, ace, ace, ace,   ace,   ace,   ace,   ace, ace, ace,   ace   (11   total)
21
2, 4,   6, jack
22
king,   ace
21
10,   5,   10
25
Note: suits don’t   matter in   Blackjack, and   Blackjack uses   multiple   hands   so   more than   4   of the   same   value   card can appear   in   one   hand.
Your score   method will   likely   remove   items from the stack to count the score.   Remember to   add the   items   back   before   returning. The order of a   Blackjack   hand does   not matter.
Here   is   some   sample   output   from   running   Lab5   .java   (note, this   uses   a   random   number   generator   so   your card values will likely be   different   than   mine):
Starting new   game   of   Blackjack
Dealer's   cards:
king   of   clubs
9   of   clubs
3   of   hearts
2   of   clubs
Dealer's   score:   24
Player's   cards:
8   of   spades
ace of   diamonds
Player's   score: 19
Player   wins!
Deliverable
You are   required to submit only   HandScorer.java, a class you   created to   implement   the   HandScorerInterface. The   autograder will use the HandScorer   class that you submit to evaluate some   sample   Blackjack hands to ensure correctness.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
