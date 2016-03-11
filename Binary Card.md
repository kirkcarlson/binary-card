#Binary Deck ...or a Paper Computer
This project helps teach some of the concepts of binary or base 2 numbers used in computers. It uses a set of 32 cards each representing on number between 0 and 31 in both decimal (base 10) and binary (base 2) formats as well as the converstion process between the two.

This project demonstrates:

- binary encoding of numbers
- a binary search technique
- a binary sort technique


##Files
* Binary Card.xlsx is a Microsoft Excel spreadsheet used to generate the card deck.

* Binary Card.pdf is a more potable .pdf version of the card deck.

##Construction
* Print the PDF on card stock or construction paper. Hopefully it fits. (this may take some work to get right, perhaps changing the scaling factor).

* Cut out the individual cards (32).

* Punch five holes in each card, aligning the punch with the top of the black square or rectangle.

* Cut out the black rectangles completely. Try to cut a tapered slot bigger at the card edge and to the edge of the punched hole. 

##To use to find a number

* Optionally shuffle the cards

* Get a number between 0 and 31 inclusive.

* Have them tell you the binary representation of the number that they provided.

* Working from one end or the other of the binary number:

	* put a stick through the hole representing a bit and separate the working deck into two halves. Shaking the cards helps.

	* if the bit is supposed to be a zero keep the cards on the stick, otherwise keep the cards that fell out.

	* With the cards that you are keeping, repeat the above steps for the other 4 bits.

* You should end up with the one card that was desired.



##To sort the deck:

Work from the low order bit to the high order bit.

* Optionally shuffle the cards

* Start with the low bit

* separate the deck into two parts -- 0 cards and 1 cards for that bit

* put the 0 cards in front of the 1 cards (based on the card faces) to form the whole deck

* repeat for the other four bits.

* The deck will be perfectly ordered.

Note: if you put the 1 cards ahead of the 0 cards consistantly, the deck will still be sorted, but just in the opposite order.

