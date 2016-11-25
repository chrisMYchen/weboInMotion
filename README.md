# Webo
What is Webo? Webo is an add on package of Skills for Jibo in order to interact with emotion. Using Jibo's built in camera functionality in conjunction with Microsoft's Emotion API, we are giving Jibo the ability to empathize, categorizing facial appearances into emotions for Jibo to interpret and react to appropriately. 

##Skills

###Look At
This skill simply takes photos of the nearest person he is interacting with and processes their emotion. Then given this emotion, he will respond as if in conversation - mimicking the person's emotional state. 

####SAD
If the person is Sad, he will make a slow whirl and emit a soft blue glow. He will also say weaker toned down words.

####NEUTRAL
If the person is Neutral, Jibo will perform his basic greeting emote and a neutral phrase while emitting a green glow.

####HAPPY
If the person is HAPPY, Jibo will perform an exciting greeting, giving appropriately enthused word responses, and emit a yellow glow.


##Dependencies
We use the following Node.js packages aside from the packages Jibo already uses
+ 'fs'
+ 'request'
+ 'node-oxford-emotion'
