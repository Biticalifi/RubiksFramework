'Rubiks Framework' project by Biticalifi

Commands: 

quit - Quit the program\n
help - Show this list of commands
help2 - Shows a second list of commands

Move commands:

u - Turn the upwards face
d - Turn the downwards face
r - Turn the rightwards face
l - Turn the leftwards face
f - Turn the front face
b - Turn the back face
m - Turn the middle layer
e - Turn the equatorial layer
s - Turn the sides' middle layer

x - Rotate cube on R
y - Rotate cube on U
z - Rotate cube on F

<move> + ' - Prime turn (counterclockwise)
<move> + 2 - Half/Double turn
<move> + w - Wide turn

Cube commands:

reset - Returns the cube to its solved state and resets move history
scramble - Randomly scrambles the cube
solve - Solves the cube algorithmically similarly to the beginner method

save - Prints an ID that can be loaded using 'load <ID>'
load <ID> - Loads an ID for a save state

history - Shows your move history
undo <value> - Undoes the last <value> moves from your history
undo all - Undoes all moves from your history
redo <value> - Redoes the last <value> undone moves
redo all - Redoes all undone moves

Customisation commands:

delay get - Returns the current delay between each turn
delay set <value> - Changes the delay between each turn

colour set <int> <new colour> - Replaces a colour with any string
colour reset - Resets all colours to their default values
colours[0 = ⬜, 1 = 🟩, 2 = 🟥, 3 = 🟦, 4 = 🟧, 5 = 🟨]
