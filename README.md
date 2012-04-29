dec2cod
=======
dec2cod is a simple bash script to convert Magic: The Gathering™ decks from `.dec` and `.mwDeck` (used by [Magic Workstation][1]) to `.cod` (used by [Cockatrice][2]).

[1]: http://www.magicworkstation.com/
[2]: http://cockatrice.de/index.php?a=project

Usage
-----
Run the script when you want to convert a bunch of `.dec` and/or `.mwDeck` formatted MtG decks to `.cod`.

The script is still in an early phase and prone to bugs. The main issue will probably be the proper detection of card names, but in most cases it should work fine.