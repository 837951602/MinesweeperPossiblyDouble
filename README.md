# Minesweeper but each cell may contain two mines

I think I've seen such game before, but I can't find it.

# FAQ

* How likely does double mine happen?

I currently add mine to a random cell, unless it already contains two mines. According to test, this seems a reasonable ratio.

* Why it doesn't claim a win even if I flagged all mines and revealed all safe cells?

Find if you missed some position where it should be one cell of double mine than two cells of single mine.

* Does it support IE?

I tested on IE 6, It works fine except lack of font, resulting `💣` and `🚩` not showing.

# TODO

* Adjust difficulty
* Beautify (maybe introduce some image)
* Display idea when flag and mine don't match
