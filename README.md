# NBA-Fantasy-LineUp-Builder
NBA Season LineUp Builder for Draft Kings and Fan Duel

This program takes the input of the Stats sheet from Basketball Monster and the CVS files from FanDuel. Matches Names and Ids with stats, and projections for use for line-up creation.

If inputting a Basketball Monster Cell Sheet(example included) you’ll what to start at the Start Here Comment. The p1x..p2x..etc. Refer to player id numbers that you want in your line up. Whichever path whether GPP/Quin 2 to 3 players. The results will push out to the workbook and you can drag those directly into draft kings or fan duel depending on what sheet you used for the ids.

This program will create all possible combinations with projections.

Special notes for this program:
Cython is used to increase the speed of the process of running the line-ups. Arrays are used in lieu of Dataframes so it takes less process time and is faster as was categorical data.
