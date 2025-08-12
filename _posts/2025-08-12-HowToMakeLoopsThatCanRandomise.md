---
title: Make Loops that can be Randomised
author: 
date: 2025-08-12 17:06:31 +1200
categories: [Learning]
tags: [game, learn]
---
The typical way to create a loop for use in a game is to take our audio file and make an edit in the middle. Then, we can swap the two sections over, so that the start now becomes the end. This ensures that the audio file will loop perfectly as the end point will perfectly lead into the beginning. Then, we add a crossfade so that there is no clear edit in the middle.
{: .text-justify}

![BasicLoop](assets/RandomisedLoops/BasicLoop.png)

<sub>Above: A basic loop created by swapping the first half and second half and adding a fade.</sub>

The key aspect of this that allows it to loop seamlessly is that the end of the file perfectly leads into the beginning. This is the trick we can exploit to create more loops that will still connect seamlessly to this basic loop we have already made. As long as we retain the very beginning and ends of our loop, it will loop seamlessly. So, we can edit out the entire middle section of our basic loop and replace it with different audio to create a new variation.
{: .text-justify}
![BVariationLoop](assets/RandomisedLoops/VariationLoop.png)

<sub>Above: A variation loop created by replacing the middle of the basic loop while fading into the same beginning and end.</sub>

You may think the start and end points will be noticeable as they are the same every time. However, by selecting the right moment and by having the fades go right up to the start and end points, we can make it very hard to notice this reoccuring material. It can also be beneficial to vary the length of each loop so that the loop point does not recur at a fixed rate. 
{: .text-justify}

If we have a looping sound that the player hears for an extended period of time, it can be worth it to implement loops that shuffle in this way so that there is more variation than an implementation that uses a single loop.
{: .text-justify}

These assets can easily be implemented using FMOD Multi-Instruments or Wwise Random Containers. 
{: .text-justify}

If you would like to watch a video explaining this principle, here it is:
<div class="video-container">
  <iframe class="video" src="https://www.youtube.com/embed/uHGDUUyrIVY?si=XtIJaz6ZG1BSVzsJ" frameborder="0" allowfullscreen></iframe>
</div>

