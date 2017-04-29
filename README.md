# What I got so far :)
My ventures into programming games and what I've learnt so far!!


SO FAR:

Resources I have gathered:
- first person example map
- some starter content/code
- 3D hand model from the open source web 

IN THE PROCESS OF:
- making an AI that follows you and has range

Coded so far:
- tracing using the camera
- prints what I have pointed at
- traces when I left click
- trace has range
- object that has PHYSICS comes to me when clicked on and traced over (without physics it stays)
- when clicked on cone it spawns objects I can pull
- aiming at cone and clicking spawns cubes from the cube blueprint class
- when cubes or anything is overlapping on box, it gets teleported to teleport zone...
- I (player) doesn't get teleported.
- when cubes are teleported it adds to a counter so when it hits 3 it'll teleport the lander that the cubes are teleported to
- the lander goes towards a sqhere I placed into the game. (means that it can go to any component I set it to go towards
- bridge is now walk acrossable
- AI implememnted in there: if you walk in its radius, it will follow you. if not it will wander around

Some stupid bugs :
- !!!!! FIXED -using casting method? !!!!! when spawned from the cone, cubes somehow get stuck there now... fricking had it right before
- when cubes are teleported, they are LITERALLY TELEPORTED. Jeez, i wanted more of a sweeping motion
- shadow stays when I deleted a static mesh from my map?? dumb.
- the bridge will keep on building when i keep putting material onto a certain volume.

Want to do??:
- (c)create volume that static mesh 'clicks into' 
- ^^^^// so scrap this idea, we just want a method to transport blocks on trigger overlaping component to build into some sort of structure..//
- (a)maybe make some material
- (a) rip medieval town models and textures online... yay
- //done (c) make followers?? (kind of just want to flex my knollege in AI hehe)
- (c) make the followers bring up a widget that asks if you want help: if yes they will follow, if not they will stay and wander till you specifically ask them to again
- (a) get villager bodies - ye olde 3d pixel art models
- (c) make database of speech stuff for my ghosts
- find things to do..

Theme so far/story boarding:
- I seem to like the single creepy hand
- Takes place in: forest type place but i want cute aesthetic lighting of blue and green lights the size of dust particles - hard to explain but yeah
- aesthetic: halloween type characters but in a more cute like pixel way. :)
- story: You are basically a hand with the power to bring things toward you (really heavy things like rocks and stuff) and you start off in this forest. The forest is inhabited by ghosts who want settlement in the forest (houses, bridges, etc.); nevertheless, they can't physically pick stuff up because they are, well.. ghosts. So you must use your cool powers to help pull material from your surrounding and build settlement for these helpless, yearning beings.

Stuff figured out so far:
- Casting: when you want to dive into another class blueprint and change it from the blueprint casting it. - More research needed.
- Dealing with component vectors, how to transform them and the method to use thats not hard coding ;).
- learning behavior trees - nodes + blackboard stuff (what i have enjoyed most)
- implementing an AI's behaviors and conditionals(decorators) 
