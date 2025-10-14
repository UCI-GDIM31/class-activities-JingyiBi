# in-class-activities
## Devlogs
### W1
Hello World!

### W2
The r, g, and b variables are floats because color values usually need decimals to show smooth changes between shades. Using floats lets the colors blend more naturally instead of jumping between whole numbers.

The _bounce variable is an int because it just counts how many times something bounces. Since that’s always a whole number, int is the right choice.
No error.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

### W3
I belong to Table 5, and I will be answering question 1.
Q: You're building a rhythm game, and you're writing a method named DidPlayerHitBeat that tells you whether or not the player accurately hit a beat based on the time that they pressed a key.
The input will include float x and float y. Float x refers to the moment when player's finger touches the screen. Float y refers to the moment when player's finger leaves the screen. In the body part of the method, we will substract y from x to obtain float z. If z is greater than 0.2s, then bool whetherHit equals true. The boolean type whetherHit variable will be the output.
Input: float x (touch time); float y (leave time)
Output type: boolean
