# Meeting

•	This meeting was rather short as there wasn’t too much to discuss but it was rather a progress check. I presented the issue with the camera perspectives on the portal to Barrett and Arnaud. They suggested what I need to fix the distortion which was to make the player’s angle relative to the entrance portal equal to the angle for the camera at destination. (See attached picture).

![
](week9image1.png)

# Development
•	This week, I continued development on VR navigation methods. I decided to focus on development of allowing the user to ‘shoot’ a portal to a wall or object and it would create the portal. To allow the player to see where they are shooting towards, we used a similar pointer renderer (like when we are implementing basic pointer teleportation in the earlier weeks) to show where it will hit. 
•	The portal would be spawned by moving it at that specified location and setting it as active. However, it was quite a challenge to get it to rotate towards the direction so that it is flat with the surface.
•	I was able to figure out that what I need was the normal vector to set the rotation to align with the wall.

![
](week9image2.png)
•	After figuring that out, I was able to implement the spawning of portals without problems however, it is still buggy. Firstly, when it is shot to a wall, it also displays partially (as it is a plane and needs to move forward a little bit). Also, when it is shot against game objects (e.g. barrels) it would pierce through it and look unnatural. Lastly, as the portal is currently a plane, it doesn’t look like a portal. 
# Goals
•	Combine portal with map functionality 
•	Fix the three issues outlined in relation to the portal and the camera perspectives on portal


