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