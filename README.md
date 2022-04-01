﻿# Get-WordleList
This script was my attempt at beating Wordle as quickly and as often as possible

It's use is simple

There are 4 requested inputs

Letters Found
A current list of Letters that have been found in the solution, whether they are in the correct or incorrect position is not relevant

Letters Rejected
A list of all letters that been used but not found, you can type the same ones twice if needed from Wordle Lines

Pattern Match
A current Pattern of Found letters in correct positions. a '.' holds the position for non identified characters in these positions

Pattern Rejected
This is an ongoing array of Letters found but in the wrong position.

Letters Found : This can be overwritten at any point in time with a new set

Letters Rejected : This will present the current list, you can simply add to this list each time.

Pattern Match : Examples of Pattern Match

A in the current first Position
A....

B in the Last Position
....B

A in the Second Position, B in the third Position
.A.B.

Pattern Rejected will follow the same structure.  Just keep entering the individual patterns and hit enter.
These patterns are actually just regular expressions.
