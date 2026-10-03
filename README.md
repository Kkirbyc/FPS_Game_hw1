HW1 - First Person Project
Unreal Engine Version: 5.0.3

SUBMISSION LINKS
Video Demonstration (YouTube):
https://youtu.be/6LD3QZZxUdY

Project Files:
https://github.com/Kkirbyc/FPS_Game_hw1

PROJECT OVERVIEW
This project uses the Unreal Engine First Person template with Starter Content and demonstrates the five HW1 requirements:

1. A First Person template project with Starter Content.
2. Three instances of a custom static mesh object that automatically rotate in place when the level starts.
3. A keyboard input event that prints a message on screen when the 0 key is pressed.
4. A cylinder that activates a fire effect when the player collides with it. The Blueprint uses Event Hit, checks for BP_FirstPersonCharacter, and activates the fire component. The fire is a child of the main static mesh (Barrel).
5. A light switch trigger that toggles a Point Light each time the player enters the trigger area.

CONTROLS
W / A / S / D: Move
Mouse: Look around
Space: Jump
0 (top row of keyboard): Print "HW1: Key Pressed"
Walk into the white cylinder: Activate fire
Enter the light switch trigger area: Toggle the light
Leave the trigger area completely and enter again: Toggle the light back

OPENING THE PROJECT
1. Download and extract the project files if provided as a ZIP archive.
2. Open HW1.uproject using Unreal Engine 5.0.3.
3. Open FirstPersonMap if it is not already loaded.
4. Click Play, then click inside the game viewport to control the character.
5. Press Esc to stop playing.

VIDEO GUIDE (APPROXIMATE TIMESTAMPS)
00:00 - Project and template overview
00:37 - Content folders, including StarterContent
01:17 - Three rotating objects
01:32 - Keyboard-triggered text output
01:52 - Player collision activates fire
02:17 - Light toggles on and off
02:47 - Fire Blueprint and component hierarchy

The demonstration was recorded using OBS Studio.
