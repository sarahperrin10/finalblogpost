# Reflecting on My Final Project
------

### My Final Blog Post

<b>Project:</b>
The Most Popular Shows on Netflix By State, Extended

<b>Conceptual Description:</b>
When I first saw information about this topic displayed on “HighSpeedInternet.com” I was immediately interested in looking at what states watched what shows. However, I found that their graphic was very difficult to make out as a viewer. The background is a mess of ugly grey colors, the show names often extend beyond the boundaries of the states’ outlines, and sometimes it is hard to visualize the shows written on the map even though their names are there. There is just an overwhelming amount of writing on the screen at once. In addition, one could only connect a show to its corresponding state if he/she has a perfect sense of U.S. geography. Most people do not.

In my project, I wanted to take this same information, but display it in a much more user friendly way, incorporating color, pictures, and the names of states as well, so people without knowledge of geography can also follow along. I hope users absorb the information I have displayed here in a way that feels like fun learning. I hope that they take to my sketch like an exploration, rather than an information dump. In addition, I think that my sketch deals with the expansion of Netflix as a brand as well. Netflix extends across the country, connecting all of us. Their original shows are household names. Even without watching many of the shows depicted on this map, many people would recognize the names/images and also recognize them as Netflix-created shows. Given the way that Netflix has transformed the way that consumers watch television, I think it is fitting to provide a national graphic such as this one.

<b>Interaction Description:</b>
My piece begins with a title page that introduces my topic (“The Most Popular Shows on Netflix by State”) and then gives directions to move onto the next scene (to press the right arrow key). The next scene is a computer screen that gives the user directions on how to interact with my piece (they must click on each state abbreviation). The final scene is a large, green On-button (like on a remote control) that links to the interactive map.

Once on the map, the user can click on each abbreviation and the  corresponding show image/name will appear inside a television screen. The image and name jitter randomly, just like static on a screen might. I have also taken out the cursor on the map and replaced it with a cartoon remote control. In addition, on the top of the screen, there is a link back to the title page, and a link to my source (HighSpeedInternet.com)

My piece is laid out easily for user interaction. None of the abbreviations are crowded on others, the show image and name are displayed clearly in the middle of the screen, and the user has to only click once to see this information, and then click again to get rid of it. My intended audience is mostly teenagers and young adults, those who often watch Netflix. I also think this is a graphic that Netflix as a corporation, or even the shows depicted here, would find useful for understanding their market and what states different shows succeed in versus other states or regions. Overall, the interactions in my piece have updated the original graphic on HighSpeedInternet.com to a degree that my project now better matches the formidable essence of Netflix, both as a brand and as a consumer product.

<b>Extension:</b>
I extended my third project in numerous ways. One of the most obvious ways is that I added multiple scenes before the actual graphic. I think that it helps to give a general idea of my project and user directions before the map, which in and of itself is very busy. Before, I had the directions and title all on one screen with the map. In addition, I think the scenes I included help to establish a theme of pervasiveness concerning Netflix in our daily lives, and these symbols (the faded out Netflix home page, a green on-button) that we so readily recognize. These scenes build anticipation to the main event.

In addition, on the actual map I changed the way the user views each show image and name. Before, when the user would hover over the abbreviation, the show image would display over it and show name would display at the top of the page. Now, the user must click on the abbreviation and both image and name will be displayed in the middle of the screen inside a television. I think that this change makes my map much cleaner and easier for the user to interact with. Previously, it was difficult to tell exactly what state the user was hovering over, and the images looked clunky spread out across the screen. But with a clicking feature and having the show image/name displayed in the middle of the screen, the information is concentrated in the same place every time. Overall, I think that my extension succeeds in further developing my conceptual idea of wanting a cleaner, more fun version of the original graphic I found, as well as making interaction easier for the user in general.

<b>Sketch of Extended Piece:</b>

![Sarah Perrin](images/outline.png?raw=true "Sarah Perrin") 


<b>Technical Details:</b>
I used P5.JS for my project and posted it on GitHub. Though it was difficult to create a map in P5 and hard code the coordinates of each state abbreviation, I found that I had much more creative freedom elsewhere to enhance my project. I loaded the data from a table on a CSV file and then created a “State” class that would include the state's abbreviation, its respective position on the map, the show name, and the show image. 
![Sarah Perrin](images/screenshot3.png?raw=true "Sarah Perrin")

Inside this class, I had to create a "showStates" function that would display the state abbreviations first and be separated from the TV/show display interaction. I also created a “clicked” function to check if the mouse had been pressed at a state abbreviation. Inside display, if “clicked” was true the corresponding show image and name for that state would be displayed in the center of the screen. I also created a “move” function that would make the show image and name jitter inside the television, shown below:

![Sarah Perrin](images/screenshot2.png?raw=true "Sarah Perrin")

In terms of the scenes I created, I had three different animations, which I connected to one another by a “keyPressed” function, the key being the right arrow.

![Sarah Perrin](images/screenshot1.png?raw=true "Sarah Perrin")

The rest of this code in scene manager was pretty straight forward. In the last animation, I used a hyperlink on the green on-button to link to my interactive map, which is a separate GitHub page. If the mouse is pressed, and the mouse is also within a certain distance to the coordinates of the on-button, then this new window will open. 
![Sarah Perrin](images/screenshot4.png?raw=true "Sarah Perrin")


<b>Link to Project’s Full Code:</b>
<p><a href="https://github.com/sarahperrin10/finalproject">Link to beginning scenes' code</a></p>
<p><a href="https://github.com/sarahperrin10/finalprojectmap">Link to interactive map's code</a></p>
