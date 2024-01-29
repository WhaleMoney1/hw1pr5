# hw1pr5
homework 1 part 5

Exersice 1:

part 1: the only diffent unique states it will be in are:
xxxx,Nxxx,xExxx,xxWxx,xxxS,NExxx,NxWx,xExS,xxWS
the picobot does not need to remember every simgle step it takes, for instance if the surrounding looks like xxxx, its only job should be to move forward until its surrounding changes, for instace it meets a wall

part 2: if the picobot starts in the lower left corner and assuming its facing north we can tell picobot to move north until it reaches "NxWx" then turn clockwise move forward again turn clockwise and then move forward until it reaches xxxS. once it reaches that, turn counter clockwise, move forward turn counter clockwise again and then move forward until i reaches Nxxx. Repeat the last two commands until picobot reaches xExS, turn counter clockwise one more time and move up until it reaches NExx. Then the whole area should be covered.


Exersice 2:

part 1: the added random locations does not change the number of different surroundings picobot wil observe because in order to cover the whole area picobot will observe all surroundings.
if we move picobot in the bottom left corner and rotate it north we can absolutely reuse the plan from exersice 1

part 2: assuming picobot faces north we can tell it to rotate clockwise twice and move it until it reaches xExS or xxxS, in either case we turn picobot clockwise and move it until it reaches xxWS the bottom left corner. turn it clockwise one time and now its in the same position of exersice 1 and we can reuse the same plan as before.
