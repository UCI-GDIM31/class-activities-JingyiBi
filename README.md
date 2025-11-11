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

For the collider activity, I added Rigidbody components to the Cat and the SoccerBall because both of them need to move and react to physics. The Cat should be able to kick the ball, and the ball should bounce when it hits other objects. I didn’t add a Rigidbody to the Goal, since it stays in place.I checked Is Trigger only on the Goal collider. That way, the ball can pass through the goal while still letting the game detect when it scored.
When I tested my game the first time, it didn’t work perfectly—the ball went through the floor! I realized I forgot to add a collider to the ground. After I added a BoxCollider to the ground and adjusted the sizes of the other colliders, everything started working correctly.
### W5
Question:
What direction does Vector3.forward point to? Is it related to the camera’s direction?
Answer:
Vector3.forward points along the positive Z-axis in Unity’s world space.
It is not directly related to the camera’s direction — it just means “forward” in global coordinates (0, 0, 1).
However, if you use transform.forward, then it refers to the object’s local forward direction, which can change depending on how the object is rotated.

DeerW5:
1. add component DeerW5 to the inspector of gameObject Deer
2. define float variables for deer's speed that can be shown and changed in unity
3. an Update() method, deer will move every frame after the game starts
4. use transform.translate to change direction
5. use GetComponent<> to find NavMeshAgent
6. use Collision() method to make Deer stop when it touch the target object
7. add collision and rigidbody to mushroom-red
Renew:(written after coding)
1. set target and drag red mushroom to target, member variable target with type Transform
2. use Update() and GetCOmponent<> to locate and use NavMeshAgent component
3. use unity method setdestination() to set target as the destination.

### W6
https://docs.google.com/document/d/1exNqQE_zGuOoztND9FT3ldDwkXjJ6m8a8oRDWERaMyg/edit?tab=t.0
part4,5

Q1:What member variables does this class need?
public float speed,private bool _isChasing,private Transform _player
Q2:What methods does this class need? Should it be something that Unity provides (like Start(), Update(), or a collision method), or one you write?
StartChasing,StopChasing,Update
Q3:What should the method(s) do?
StartChasing(): Makes the bat start moving.
StopChasing(): Makes the bat stop moving.
Update(): If _isChasing == true, the bat moves toward the Cat’s position.
### W7
https://docs.google.com/document/d/1TsVke4FYWiPQJM1o9TWKmZdGuEjed6uXTYwZxrXfC3I/edit?tab=t.0
animation, UI


## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

