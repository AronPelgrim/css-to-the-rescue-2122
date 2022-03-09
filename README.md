# CSS to the Rescue: FIREWORK EDITION
## Asignment
The course CSS to the Rescue is about learning to create innovative, experimental, yet pleasurable user experience by using CSS and SVG. The assignment is to create a dynamic, CSS only firework show, where the user is able to influence the show. The challenge here, is that it's not allowed to use any JavaScript!

## Process
### Week 1
The first week went slow, but steady. My idea was to create a moving background with mountains, where the firework would move past. I created the mountains with the code below.
```   
border-left: 5em solid transparent;
border-right: 5em solid transparent;
border-bottom: 5em solid black;
``` 
You can create triangles like this, but it will be hard to make them move. That's when I found out that you can also create triangles with a ``` conic-gradient. ``` This in combination with keyframes, made it possible to make my background move. The next step was to create the firework and make it interactive.

<img width="1128" alt="image" src="https://user-images.githubusercontent.com/74137185/157466593-a2e5d1f4-4b40-4be2-b417-0a2a33bd1e2e.png">
Image of my first attempt of the mountain.


<img width="1128" alt="image" src="https://user-images.githubusercontent.com/74137185/157468741-f08c6e98-14c2-4144-8f8e-9bab117dc9ac.png">
Image of the added green moving mountains, created with conic-gradient.

### Week 2
In this week, I focused mainly on animating the firework bomb. At first my idea was to connect two animations two the firework bomb. This was a dumb idea, because I forgot that you can't connect two animations to one element. The solution was simple, creating one long animation. Another problem I ran into was that the ```animation-iteration-count``` only worked on infinite. After some frustration, I found out that the 0% in the animation had to contain code for the animation to work. I also added a fire-engine to the bomb and also an explosion with a delay that activates when the bomb drops. A small styling issue was that the mountains didn't move properly. The closer mountains moved slower then the further mountains and this perception isn't right, it's the other way around. So I changed this.
