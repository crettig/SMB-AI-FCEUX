Github clones of MarI/O by SethBling

This version is modified with 2 changes from
sethbling's code.
1) Added a function to scan find out whether or not the game
was in a "normal" state, which essentially just means that Mario
is running around on a level and not in a pipe, falling down a 
flagpole. etc. If mario was not in a normal state, the timeout is
reset.
2) The second change was to add .5 to the fitness of genome 
for every frame that Mario was not in a normal state. This way
a genome can be encouraged to move onto the next level.

Also Took the port of FCEUX for Sethbling over Bizhawk as I found FCEUX to be much faster
https://github.com/juvester/mari-o-fceux <--- see here for original code

Taken from https://www.youtube.com/watch?v=qv6UVOQ0F44

MarI/O is a program made of neural networks and genetic algorithms that kicks butt at Super Mario World.

Source Code: http://pastebin.com/ZZmSNaHX

"NEAT" Paper: http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf

Some relevant Wikipedia links:

https://en.wikipedia.org/wiki/Neuroevolution

https://en.wikipedia.org/wiki/Evolutionary_algorithm

https://en.wikipedia.org/wiki/Artificial_neural_network

BizHawk Emulator: http://tasvideos.org/BizHawk.html

SethBling Twitter: http://twitter.com/sethbling

SethBling Twitch: http://twitch.tv/sethbling

SethBling Facebook: http://facebook.com/sethbling

SethBling Website: http://sethbling.com

SethBling Shirts: http://sethbling.spreadshirt.com

Suggest Ideas: http://reddit.com/r/SethBlingSuggestions
