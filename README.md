# RickyBlitz
code for my new video game that I am working on, this way I can get back some of my code if I loose my files again. Feel free to borrow it if you want!

for the player controller This script allows my player to move and jump but also works for some abilities I've added such as wall jump, wall climb, Slow-Motion,
and Higher jump. I also added a dust trail that follows the player whenever you jump using Unity's particle system. MoveSpeed is set to 10, JumpForce is set to 17.55,
GroundLayer is set to a custom layer mask I just called ground (I then put this on every platform) Ground Radius is set to 0.2, WallJumpTime is set to 0.2, WallSlideSpeed
is set to 0.3, WallDistance is set to 0.55, and JumpTime is set to 0.35. I also added a PhysicsMaterial2D to the player and set the friction to 0 so that he would stop getting 
stuck on the edge of platforms. ps. (I made the player a prefab as well.)
