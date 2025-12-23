CSCI 191
Jimmy Sanchez
Midterm

1. For loading the different scenes I created a load and reset function within the scene class. The load function initializes all the different textures that will be used in the next level. The reset function resets all the positions for the player, camera, and obstacles as well as any animations.
2. For changing the scene, the player slowly changes position from the beginning of the level to the end, and upon passing a certain point the level is complete.
3. The 3D model was loaded with the model loader.
4. The camera was set at a certain position behind the player and moves forward at the exact same speed as the player to keep the distance consistent.
5. The player moves forward automatically and can switch between the lanes with the left and right arrow keys.
6. A new class called barrier was created to load in the different objects that will be used as obstacles in the scene. During initialization, they are given random positions.
7. The player runs forward, as well as the objects moving toward the player. As the level count gets higher, they move positions at greater speeds.
8. Upon collision, the player loses one health point, and after 5 hits the player is dead.
9. The reset function is used to send the player back to the initial point and all the objects are set to new positions.
10. At the start of each level, the player is given all health back.

Bonus: The player has 5 lives to get through each level. At the start of each level all lives are restored along with health. At the end of each level, the level count and run speed continually increase, looping between the three scenes. Stats are displayed to show the level, run speed, health points, deaths, and lives of the player. If the life counter is to hit 0, the player has lost the game and is sent back to level one with speed being reset as well.