# Set up the Race Track
### @flyoutOnly true
### @hideIteration true


``` ghost
     for (let index = 0; index < 2; index++) {}
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```

```template
   //     
```

## Step 1
Let's set up the antennas to count the score for the race. Have your agent visit the marked spots using ``||agent: agent move forward||`` as well as ``||agent: agent turn||``. Study the walk pattern first and then run your code on the``||Loops:on start||`` block.

### ~ Hint 
There are multiple ways to solve this. You can also make use of  ``||loops: repeat||`` blocks. Try to find the shortest path
```  blocks
agent.turn(LEFT_TURN)
for (let index = 0; index < 2; index++) {
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
}
agent.move(FORWARD, 6)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 10)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 4)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 6)


```
