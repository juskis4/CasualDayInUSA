# Blog Nr.1

## Roll A Ball game

The game was made using Unity and following it's wonderful tutorial "Roll-a-Ball".
The game is very simple and straightforward, as the only goal is to collect all the yellow spinning cubes with a ball that the player is controlling. The cubes were made as Prefabs, while the walls are not, so there is still room for improvement here.

During the development, I got stuck only once. In the PlayerController.cs script, I tried initializing the player's position values (movementX, movementY) in the Start() function, rather than in OnMove(). That was a stupid mistake from my side, which I quickly noticed, after checking the console in my Unity project.

The tutorial also suggested to try and set the camera object as a child to the Player object. At first I thought that the camera would just follow the players movements, and it did, but not the way I expected. As the player is a sphere, the camera was attached to one axis and was spinning together with the sphere. To simply put it, that changed the game from Roll a Ball to Washing machine simmulator.

Overall, even though this game is very simple and does not have much to it, it is still an achievement to me as it was my first created game ever.