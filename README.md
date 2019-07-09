This is a wonderful website showcasing my various projects, a list of which is below:

- [x] Jitterbug
- [x] Roomba
- [x] Drone imaging projects
- [ ] SAR UAV
- 253 Robot


## Hallway-Navigating Roomba

In Fall 2017, as a project for a robotics course, I worked with two others on modifying a Roomba iCreate development platform to navigate its way down a hallway, using only a camera and onboard image-processing software. 

To do this, we utilized a Raspberry Pi 2 running Python code to analyse an image of the hallway ahead of it, pick out the lines formed by the intersection of the hallway and the walls, then find the vanishing point of the hallway. From this, the robot could navigate itself down the hallway without a need for bump sensors and other methods of navigation. A video of it in action is below.

<center>
<video width="650" height="366" controls preload> 
    <source src="roomba.mp4"></source> 
    <source src="roomba.webm"></source> 
</video>
</center>

Additional navigation methods were planned for the robot, such as determining when it arrived at a corner, and mapping capabilities to allow it to find its way back 'home', but our team ran out of time in the semester to implement them all.


<!--We were inspired by a project from the Universidad del Valle, Cali, Colombia, in which they utilize a similar algorithm to detect the lines of the hallway and compute the logical way forward.

<iframe width="650" height="480" src="https://www.youtube.com/embed/NC7mKUrJOE0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
## Drone-based Terrain Model Generation and Elevation Mapping

As a project for 3vGeomatics in Spring 2017, I was a part of a three-man group working to find a better method of producing elevation data of sites for geographic applications. We decided to utilize footage from a drone flyover to generate a 3D model of the area using photogrammetry.

Our initial test run of the software utilized six screenshots from Google Maps' 3D terrain feature, and produced excellent results, as seen below.

<div class="sketchfab-embed-wrapper"><iframe width="650" height="480" src="https://sketchfab.com/models/684fe805ccb546b6ad01d56f9e56f2e2/embed?camera=0" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

As can be seen, the software we utilized accurately captured the terrain and buildings in the test area. We were able to utilize a drone to take images of a cliff face near UBC, and translate that into a 3D model and elevation map, as seen below.

[image]

This process is much more accurate, flexible, and cheaper than relying on public domain elevation data or aircraft mapping runs. 3vGeomatics was very happy with our results and intended to use this process regularly in the future.

## Wire-following/Musical Robot

[image of jitterbug]

In Spring 2015, I was part of a group project to build and program a robot capable of following a wire. It accomplished this task by carrying several inductors on its underside, allowing it to sense the magnetic field coming off of the wire. The robot was powered by an Arduino board, and I contributed to the C-like code to enable our robot to be one of the fastest in the class.

In Summer 2017, I repurposed the chassis of the robot project into a more entertaining role, by implementing a piezo buzzer into its electronics, and writing more Arduino code to allow the robot to 'sing' part of the song 'Wake Me Up Before You Go-Go', while moving to the beat. Precise timing control was required to allow the single instruction processing queue of the processor to allow for both sets of actions to occur. A video of the finalised product is below.

<center>
<video width="650" height="366" controls preload> 
    <source src="jitterbug.mp4"></source> 
    <source src="jitterbug.webm"></source> 
</video>
</center>



