# Cosc310Group7
## Yeet the dishes chat bot
There is now a basic GUI that has a menu system as well as chat screen.
The chat bot also provides, in the console, data of messages sent.

## External Lib
Lib: https://opennlp.apache.org/
Tutorial: https://www.tutorialspoint.com/opennlp/opennlp_environment.htm

## GUI
The gui is fairly well formated and SHOULD work regardless of the display size.
The gui is full screened and does not have an option for windowed.
the gui does not allow the user to send messages with symbols(+, -, $, &...).

## Data
This data uses the 3 toolkits we implemented.
The first toolkit tokenizes the messages.
The second toolkit adds tags and probabilities to the toolkits.
The third toolkit uses those tags and provides the LEMMA of each word.

## Example
If the user types "Where is my food?". The AI will provide a response in the GUI. The AI will also print out the following in the console:

Token	:	Tag	:	Probability
---------------------------------------------
where	:	WRB	:	0.854114026602201
is	:	VBZ	:	0.8976326825382562
my	:	PRP$	:	0.96331011384047
food	:	NN	:	0.9971238127402574
?	:	.	:	0.975736940559756

Printing lemmas for the given sentence...
WORD -POSTAG : LEMMA
where -WRB : where
is -VBZ : be
my -PRP$ : my
food -NN : food
? -. : O
