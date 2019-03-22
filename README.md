# What I got so far :)
My ventures into programming games, open source resources I've gathered, and what I've learnt!!

### SO FAR:

Resources I have gathered:
- first person example map
- some starter content
- 3D hand model from the open source web 
- 3D bread model + it's material
- 3D minecraft pickaxe model :^) + it's material 
- mixamoanimpack -> free from marketplace in ue4
- GTFreeMaterials -> free from marketplace
- Foliage -> .rar pack from forum

### IN THE PROCESS OF:
- making an AI that follows you and has range

Coded so far:
- tracing using the camera
- prints what player is pointing at
- traces when player left click
- trace has range
- object that has PHYSICS comes to me when clicked on and traced over (without physics it stays)
- when clicked cone spawns objects player can pull
- aiming at cone and clicking spawns cubes from the cube blueprint class
- when cubes or anything is overlapping on box, it gets teleported to teleport zone...
- player doesn't get teleported.
- when cubes are teleported it adds to a counter. When the counter hits 3 it teleports the lander that the cubes are teleported to
- the lander goes towards a sphere placed in the game (means that it can go to any component the player sets it to go towards).
- bridge is now crossable
- AI implemented in there: if you walk in its radius, it will follow you. If not it will wander around
- if you go in the inner radius of the AI's sight, it will pull up a widget (UI) that will ask you if you need help
- once you answer if you do or do not need help, widget will close and wont open up again
- made a pickaxe animation appear to pick at the rock. made it loop and reverse on play. - this will let the player know they can pull     from the rock

Some bugs :
- FIXED (using casting method): when spawned from the cone, cubes somehow get stuck there now (was correct in earlier version)
- when cubes are teleported, they are teleported instantly. Wanted more of a sweeping motion
- shadow stays when I deleted a static mesh from my map?
- the bridge will keep on building when the player keeps putting material onto a certain volume.
- when AI comes up to you and asks if you need help, even if you click no it will continue to follow you

### TODO:
- want a method to transport blocks on trigger overlapping component to build into some sort of        
- COMPLETED: maybe make some material
- rip medieval town models and textures online
- COMPLETED: make followers? (just wanted to use AI here)
- COMPLETED: make the followers bring up a widget that asks if you want help: if yes they will follow, if no they will stay and wander     until you specifically ask them to again
- get villager bodies - ye olde 3d pixel art models (currently a human model placeholder)
- make database of speech stuff for AI (AI already has some speech element but will need to implement database for further                 complicated speech)
- refine the bridge aspect so it doesn't build past the sphere element (maybe do a cube count? difficult due to possibility of large       structures)
- refine the cube spawner so it won't rapidly spawn every time you click, maybe it delays a bit
- find things to do..

Theme so far/story boarding:
- I like the single creepy hand
- Takes place in: forest type place but I want cute aesthetic lighting of blue and green lights the size of dust particles 
- aesthetic: Halloween type characters but in a cute pixel-based way
- story: You are a hand with the power to bring things toward you (really heavy things like rocks and stuff) and you start off in the     forest. The forest is inhabited by ghosts who want a settlement in the forest (houses, bridges, etc.); nevertheless, they can't         physically pick stuff up because they are well... ghosts. So you must use your powers to help pull material from your surrounding and   build settlement for these helpless, yearning beings.

Stuff figured out/learning so far:
- Casting: when you want to dive into another class blueprint and change it from the blueprint casting it. - More research needed.
- Dealing with component vectors, how to transform them and the method to use that is not hard coding.
- learning behavior trees - nodes + blackboard stuff (what I have enjoyed most)
- implementing an AI's behaviors and conditionals(decorators) 
- how to deal with variables to and from blueprints (blueprint communications)
