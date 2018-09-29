# Meeting

•	During the meeting, we continued to discuss more literature review material, so we can build on our understanding. Our supervisors advised an additional 3 more papers from what we already have will be adequate for our review.
•	We also continued to brainstorm different ideas for navigation methods that we can implement. Some of the ideas include the use of ‘portals’ or using a ‘map’ which is on a person’s hand and they can choose a destination to teleport to. 
•	Barrett also suggested that as the mesh may be too difficult to clean up during time timeframe, it may be better that we focus on implementing VR methods. He suggested that we instead just use colliders to prevent the player from falling through the model.

# Research Participation
Arnaud also invited us to partake in a VR experiment he was conducting as it would help with his study but also enable us to learn how a research experiment is conducted. Through that experience, I feel more confident in designing an experiment and also how to conduct it. 
# Development
•	We decided that it would be better to implement version control using Unity Cloud rather than a platform like GitHub or GitLab. It provides many benefits such as native integration with unity and support for larger files to be uploaded to. However, the drawbacks are that to support more than three users, it would mean that it would cost a monthly fee. For our use case however, that should be manageable as we can share it with one of our supervisors. 
•	Continuing development, I explored the options into using a map on a hand to teleport to a specified location. Currently, we have a simple block with buttons to test teleportation. When a player points a laser towards the button, it would invoke an event and that would then subsequently teleport the player to another location.
•	I also fixed the collision problem that we have faced earlier that enable the user to move through the wall. This was achieved by using the VRTK_Body_Physics script which added physics to the CameraRig. A basic capsule game object was associated with the physics to act as the player body. 
# Goals
•	Implement more navigation methods
•	Continue literature review

