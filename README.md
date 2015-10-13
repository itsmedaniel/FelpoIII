# FelpoIII
FelpoIII is a chess engine written in C#, based off of the FelpoII chess engine by Felice Pollano. 
Currently, a major reworking is in progress, during which the engine will become entirely anew.

FelpoIII uses a 0x88 chess board representation. For more information on this type of board representation, 
see http://chessprogramming.wikispaces.com/0x88

Currently FelpoIII, like FelpoII (but not FelpoI), uses a Mersenne Twister Generator for its Zobrist hashing.
This is maybe not the easiest, but is the most widely-implemented way to prevent collisions. For more information on 
Zobrist hashing, see http://chessprogramming.wikispaces.com/Zobrist+Hashing or see the Wikipedia entry on the subject. 
For more information on Mersenne Twister Generators, see https://en.wikipedia.org/wiki/Mersenne_Twister.

FelpoIII can be run either in the Console (Windows) or on WinBoard.

Type "help", "h", or "dir" in the Console for a list of available commands.

Email me at herodaniel@live.com for any further questions.
