# minesweeper-cli

Yes, you can now play Minesweeper in the CLI!

Rules:
https://en.wikipedia.org/wiki/Minesweeper_(video_game)

Instructions:
 - Run minesweeper.rb (ie ruby minesweeper.rb)
 - Enter coordinates (y,x) with y for row and x for column numbers
 - Chose to explore or flag
 - To explore a flagged, tile, first un-flag it

Customize:
 - Adjust frequency of bombs with argument for Board#place_bombs(d) in Board#initialize (line 7)
 - Adjust size of board with Board#empty_board(size), recommended max 12, in Board#initialize (line 8)
