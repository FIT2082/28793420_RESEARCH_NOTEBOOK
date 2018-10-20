# Meeting

•	In this meeting we discussed a bit about the report and the layout. He also suggested that we try heuristic evaluation to evaluate our project and understand the usability of our project.

# Development
•	This week a problem occurred which we did not anticipate when trying to test the portals whilst using the HTC Vive. It turns out that using the code base did not work as anticipated on the HTC Vive compared to testing it on the simulator. 
•	The first problem was that the image looked very distorted and blurry in the HTC Vive. After a couple hours of troubleshooting, I determined that issue was the displays. Although we are using the HTC Vive, the code detects the resolution as the one we see on Unity. This is a complete mismatch as the HTC Vive uses 1440 x 1600. This problem was able to be resolved by hardcoding the resolutions. 
•	The second problem was that head rotations were no longer locked and the camera perspectives on the portal appears to be zoomed. This was a major setback to our progress as we expected it to be a simple transition. Currently I’m still unsure of the problem but it appears to be related to either the screen resolution or the shader that we are using. As when we change the screen resolution, that is when the head rotations would not be locked. For now, as a temporary fix, we can change the shader to ‘standard’ which ‘fixes’ the problem but it no longer looks as realistic. We will continue troubleshooting but it is possible I would not be able to fix this as the project is ending and we still need to write up the report, prepare the presentation and also clean up the model. 

# Goals
•	Implement more navigation methods
•	Continue literature review

