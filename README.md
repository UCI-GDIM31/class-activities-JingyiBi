# in-class-activities
## Devlogs
### W1
Hello World!

### W2
The r, g, and b variables are floats because color values usually need decimals to show smooth changes between shades. Using floats lets the colors blend more naturally instead of jumping between whole numbers.

The _bounce variable is an int because it just counts how many times something bounces. Since that’s always a whole number, int is the right choice.
No error.

### W3
I belong to Table 5, and I will be answering question 1.
Q: You're building a rhythm game, and you're writing a method named DidPlayerHitBeat that tells you whether or not the player accurately hit a beat based on the time that they pressed a key.
The input will include float x and float y. Float x refers to the moment when player's finger touches the screen. Float y refers to the moment when player's finger leaves the screen. In the body part of the method, we will substract y from x to obtain float z. If z is greater than 0.2s, then bool whetherHit equals true. The boolean type whetherHit variable will be the output.
Input: float x (touch time); float y (leave time)
Output type: boolean

Class is a family recipe for how to make and present a dish that has been passed down through different generations. Components are the printed version of the recipe in a cookbook. Method is the cooking steps for this dish. Member variables are the ingredients of this dish.

The balls get brighter every time they bounce. After many bounces, this brightness adds up and eventually maxes out, turning them completely white. That's why they look extremely bright in the Scene.

### W4
table 5
line5 
 _moveSpeed is a member variable, and the type is float.
This line sets the initial value of _moveSpeed to 1.0f.
The [SerializeField] attribute allows the variable to be edited in the Unity Inspector even though it’s private.
line22
translation is a local variable, and the type is float.
This line is calling a method: Input.GetAxis("Vertical").
The method parameter is "Vertical".
_moveSpeed is a member variable, and the type is float.
Time.deltaTime keeps the movement smooth and consistent across frames.
line25
transform is a Component.
Translate() is a method.
This line calls the method Translate() on transform.
The method parameters are (0, 0, translation).
It moves the object forward or backward along the Z-axis.
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

