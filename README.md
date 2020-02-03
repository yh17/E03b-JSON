# E03b-JSON
This exercise will give you the opportunity to edit an existing JSON file (in the game-description format we are using for MSCH-C220). Fork and Clone this repository and then make the following edits to zork.json:

This is the assignment that edit JSON, allow us to get familiar to Json and text adventure game. 

 - Change the exit in FORE3 from UP to DOWN
 - Add a desc in MGRAT: "If you stay here much longer, you will be eaten by a Grue"
 - In MIRR2, add a new exit, "NORTH" with a target of MIRR1
 - In BATS, add a description: "This is a cave full of bats. They are currently sleeping"
 - In MINE7, add a new item, a "SIGN" with a description that reads "A sign is here that points down". You don't need to add a "TAKE" key/value.
 - IN FCHMP, MRDE, MRDW, MRGE, MRGW, and PCELL add a description: "You are stuck with no way out!"
 - Add new exit in BKENT called "ROB" with a target of "BKVAU"
 - In EGYPT, add a new item, a "MUMMY" with a description that reads "An ancient Egyptian mummy is sprawled on the floor". If the player tries to "TAKE" it, the response should be "You stuff the mummy in to your sack".
 - In DEAD7, change the description to "You have reached a dead end"
 - In CP change the name to "Just a room (not at all suspicious)"
 
If you need to check to see if you have produced a valid JSON file, you can validate it at https://jsonformatter.org/json-editor.

Edit the LICENSE and README.md and submit a URL to your repository on Canvas.
