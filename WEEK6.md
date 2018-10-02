<h1><a id="Meeting_0"></a>Meeting</h1>
<p>•   During this meeting, we continued to discuss about the literature review that we are conducting. We had a focus on categorising the different methods that we have encountered so we will have a better idea of what is already out there. From that literature review, Arnaud and Barrett suggested that we can pick an interesting way of navigating and try to implement a variation of it.<br>
•   We also decided that since we are beginning to development, we should use version control software like BitBucket or GitHub so that we can collaborate.<br>
•   Our supervisors advised us to continue our literature review and keep expanding it as that is part of project outcome.<br>
•   Barrett started exploring some ideas with us just before the meeting has ended. He mentioned a ‘curved pointer’ to specify destination by teleport and that is what we will try to implement.</p>
<h1><a id="Development_7"></a>Development</h1>
<p>•   We have decided that we would be using GitHub for our version control as students, we have access to private repositories which we can share with our supervisor. One problem that I have encountered already is that GitHub was never designed for large files. As our models have many images and large file types (i.e. ‘.obj’ and ‘.xyz’), GitHub will not accept it. To fix this problem, I investigated adding. gitignore files. After numerous attempts, some files were still too large to be uploaded to GitHub.<br>
•   I then investigated into Git Large File Storage which can be integrated with GitHub. This required adding ‘.gitattribute’ file to our repository so GitHub knows where to download the large files from. This allowed us to successfully add our repository to Github.<br>
•   Update: When loading the repository from another device, a problem occurred where scripts would be missing from game objects. I initially thought this was caused by not saving the scene, but the problem persists. This will need be investigated further next week<br>
•   Rather than reinventing the wheel, we decided to use Virtual Reality Toolkit to facilitate with implementing navigation. It has many pre-existing libraries, files and scripts which are tailored to VR development. One helpful feature is that it has a VR Simulator feature. As we currently do not have access to VR devices right now, it enables us to still try to implement features.<br>
•   I had explored VRTK to find out its feature. It saves us a lot of time trying to incorporate the controllers and headset into Unity as it already has built in managers that does the work for us. However, it did have some compatitiblity issues with setting up the SDK. Furthermore, controlling controller in the simulator is difficult due to its innate limitations.<br>
•   I was able to implement pointers where a user can fire a ‘laser’ like pointer and it will teleport them to a destination based on where it is pointed at.<br>
•   One issue with the implementation right now is that the CameraRig (the player) currently have no collision logic with walls which means it can move through walls. Adding a basic collider to the CameraRig doesn’t appear to have any affect and this problem will need to be investigated later.</p>
<p>#Goals Next Week<br>
•   Produce solution to fix version control<br>
•   Continue to explore more navigation methods and implement them<br>
•   Fix collision problem with player</p>