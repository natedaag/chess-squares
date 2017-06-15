# chess-squares
create a checkered square that can be used as a chess board

Write your program in the main method, or in another method invoked by main (your choice).

Use a two-dimensional, 8 X 8 array of char.

Assume all pieces are in their starting positions.

Use standard chess board orientation convention, in which the first row (row 0 for Java) is White's back rank, the last row (row 7 for Java) is Black's back rank, and the columns are numbered from left to right. So (for example), if your array is referred to with the variable board, then board[0][1] would contain (in its initial position) one of White's knights, while board[7][3] would contain the Black queen.

For the char values in the array,

Use the Unicode symbols (link is external) for the chess pieces. (To represent a Unicode code point as an escaped value in a Java char or String literal, use the code point's hexadecimal value, prefixed \u. For example, the char containing the Black king could be written as the literal value '\u2654'.)

Use the space character for any empty square on the board.

Using nested for loops, print out the chess board in 8 lines, each 8 characters long. Use System.out.print(char) for each square in a row, and System.out.println() at the end of each row, to force the output for the next row to the next line. (Don't worry about the color of the squares for now.)
