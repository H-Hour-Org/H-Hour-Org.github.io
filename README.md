 # H-HOUR 
H-Hour has been a 2 week challenge where I learned some of the Unreal's basics and applied it to a simple FPS level. Link to Youtube:
[![Preview](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unreal/HighresScreenshot00033.png?raw=true)](https://www.youtube.com/watch?v=49jHI3fC3kE)

## Making of
### Concept Phase
The map has only had one reference, Cove from COD: Black Ops 2. The reason being I wanted to keep it simple and, whilst Cove is visually pleasing, I decided to make the map stand out with far more interest points. 
![Cove](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Concept/Ref.png?raw=true)

At that moment I thought about some artificial elements that could be added on top of the natural base (water, sader, rocks, palm trees...). Those elements are the following: containers, ruins, the military base, dead fish for covers... 
![Concept](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Concept/Concept.png)

The main appeal of the level is it's flow. The player can access the middle area and go back from 3 spots, although there are another 2 which are only one way around: a ladder to the middle and a palm tree that from the middle. Each side thus has different benefits. 

Another extra element are the 3 sniper spots, one in the middle which is quite exposed and two of them as a duel on one side of the map.

### Blockout Phase
For the blockout I used the free Unity "Blockout" package (https://assetstore.unity.com/packages/tools/level-design/blockout-100388), which provides the user with many Prefabs, color palettes depending on object type (wall, floor, etc), some rotating and snapping functionalities... 
And here some images at this stage of development:
![Blockout](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unity/Blockout10.PNG)
![Blockout](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unity/Blpckout8.PNG)
![Blockout](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unity/blockout4.PNG)

### Asset gather Phase
The level had a 50+ asset database with multiple options for each one so that the chosen assets would resemble a relistic, belligerant and worn out setting.
The Sketchfab-Unreal combination was a total success since Sketchfab's models have a more organic feel and Unreal has a native .gltf importer.
Here you got a useful asset list and the mudbox:
https://docs.google.com/spreadsheets/d/1SfERhKJnwgl-50f1oxrO_vgLv_ZFZfFwCz3lS7gQ5qA/edit?usp=sharing 
![Concept](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Concept/Mudbox.png)

### Production Phase
Once the blockout was set and done and I had gathered all the needed assets, the new objective was to "dress" the blockout just as it was at that point. Here is an example:
![Dress](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unreal/HighresScreenshot00001.png)  
On top of that I spend lots of time working on the terrain, materials, trees, rocks and all the extra props needed to fill the level completely and make it have harmony:
![Dress2](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unreal/HighresScreenshot00017.png)

### Overall sketch 
This is final (flat color) top-down view of the level from which a map draft is usually made to be put in games (note that the military base is empty because it would not be seen):
![Sketch](https://github.com/H-Hour-Org/H-Hour-Org.github.io/blob/master/Media/Unreal/TopViewSchemeHighContrast.png)

### Improvements
On top of the actual level feel, there were two more interesting additions: landscape-mesh blending and vertex painting. However, many meshes such as rocks had a complex and individual material setup that hindered the progress. On top of that, Unreal's materials are set up in a way that with my configuration I could not paint more than 3 in one terrain. In regards to vertex paiting, I was experiencing some other problems and I decided to call it a day and apply these techniques in a future more simple environment. I would also have liked to add more life to the environments and a climate change with a subsequent tsunami, but we'll take about that in the future too. Now that I look at the screenshoots, Unreal has tricked me with the player capsule collider debug! :o Can you spot it? 

## Useful links
Check out the "UsefulLinks.txt" where I gathered Youtube links that may prove helpful for an "Unreal beginner". Also, in the "Media" section you will find more concept, blockout (Unity) and production (Unreal) images.  

