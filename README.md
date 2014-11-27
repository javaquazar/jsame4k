JSame4k
=======

Overview
--------

JSame4k is a puzzle game in 4 kB of JavaScript (inspired by SameGame), which
is played on a rectangular field, filled with coloured squares.
The objective of the game is to clear the field by removing groups of pieces
of the same colour. You get points for each group you remove and the larger
the group, the more points you get. To get the highest score you need to make
large blocks of one colour.

Game rules
----------
Pieces can be removed when there is a block of at least two pieces of the same
colour. These pieces will be marked when you move the mouse over them, then
they can be removed simply by clicking them with the mouse. After a block is
removed, the pieces above it drop down to fill the empty space. When a column
is empty, all columns right of it are shifted to the left. When there are no
more blocks of two or more pieces left, the game is over.

The points of a marked block of pieces are calculated by the formula
`(n - 2) ^ 2`, where `n` is the number of pieces. So try to remove as many
pieces at a time as possible to get a higher score. When there are no pieces
left at the end of the game, you'll get a 1000 points bonus.
