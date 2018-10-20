# Meeting
•	During the meeting, Arnaud and Barrett gave us access to the VR room which allowed us to begin developing and testing our implementation. We discussed that we would now have access to it anytime if it is free. This is very helpful as it would allow us to really see how it would look like in VR. Furthermore, developing using the HTC Vive rather than the VR simulator (part of VRTK) appears to be much easier, saving lots of time.

•	During the meeting, we discussed more navigation methods that we could implement. Barrett suggested that we take inspiration from architectural walkthroughs in VR where a user would select a location on a ‘map’ and the user would be teleported through it. I’m currently thinking about incorporating the use of a map to teleport in VR combined with portals. So, a user can choose where a entrance portal would spawn. The destination portal would be spawned when the user selects it on the map. Barrett proposed using cameras to mimic the effect of seeing what would be on the other side and drew us a concept on the whiteboard, so I would have a better idea of how to approach this. 

•	During the meeting, we continued to discuss the importance of the literature review for our research but also how it would benefit us by letting us draw inspiration from it. 

# Development
•	We decided that we could begin by trying to implement the portals using the method proposed by Barrett. Arnaud also assisted with this by providing a link that details how it can be implemented in Unity. Using a combination of the resources provided by Barrett, Arnaud and my own independent research, We were able to implement most of the portal functionality. Currently, it supports teleportation when a user would walk into the portal. The portal also utilises a camera placed at the destination portal to display what is on the other side before the user enters the entrance portal. This was achieved by using materials that utilises a shader. That shader is a ‘cutout’ of what the camera would see and that would be the size of the portal. 

•	A problem currently exists with the camera perspectives as when the player moves their head (rotation), the camera also moves which creates an unintended effect. Furthermore, other movements do not seem natural however, we cannot seem to figure out what is wrong, and we would need to test that in VR and get some advice from Barrett and Arnaud next week. 

# Goal
•	Fix up camera perspective issues when rendered on portal

•	Implement functionality to spawn a portal at location 

•	Combine map feature to spawn and work with portal 

