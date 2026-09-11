# Snow Surfer

<img width="538" height="302" alt="Convert to GIF project - September 10, 2026 at 19 19 11" src="https://github.com/user-attachments/assets/bc7df940-be8a-4c12-b45b-55db85acde83" />

A part static, part physics-based 2D Unity game where the player attempts to snowboard down a mountain, doing flips to collect points, without bonking their head on the ground.

## About the Project

Snow Surfer is a small 2D snowboarding game built using Unity and C#. The player can choose between a Dinosaur or a Frog, where they snowboard down a weirdly-shaped mountain, doing flips to gain points and attempting to do so without hitting their head on the ground, which would restart the level. The player "completes" a run when they get to the bottom of the mountain, where there is a finish-line flag waiting there. 

This project focused on input controls, collision handling, scene reloading, and basic particle effects. 

## Tutorial Context

This project was developed initially while following the "Complete C# Unity 2D Game Development (Updated To Unity 6)" course on Unity by GameDev.tv.

The course provided the foundation and guided implementation of the core aspects of the game itself. I used this project not only as an opportunity to familiarize myself with Unity, C#, and game development as a whole, but as a way to further my creativity skills, implementing my own game mechanics, feel, speeds, and overall design as well, implementing smoother scene reloading, as well as a smoother feel to allow the player to feel more in control of their inputs. 

### My additions

After completing and following the tutorial portion of the project, I took the liberty to extend the game, with several features of my own!

- Designed a completely different level layout for an alternative game feel
- Added sharper hills, causing for the need for more precision.
- Created a significant boost towards the end of the level, where players are able to spin their character in the air quicker, thus gaining more points.
- Added unique particle systems, signifying when different effects were active.
- Modified the lighting, environment, and color of the game.

## Gameplay and Features

- Static speed but physics-based gravity used for the snowboarding
- Mid-air rotation and trick controls
- Offset follow camera
- Scoring system based on the number of flips
- Speed boost and torque boost mechanics
- Crash and level-completion states; Scene Reloading
- Particle and camera feedback

## What I learned

Building Snow Surfer helped me develop a stronger understanding of how Unity's different systems (physics, gameplay, input, particle, etc.) work together:

- Designed half physics, have static-based movement using Rigidbody2D, learning the difference between manipulating a transform and how a physics system operates.
- Implemented aerial control and player rotation which taught me how to translate player input into responsive physics-based gameplay.
- Implemented a flip-based scoring systems, giving me experience tracking a gameplay state over time rather than responding to simple inputs and singular events.
- Learned to tune gameplay variables such as torque, speed, speed boost and torque boost strength, as well as gravity through serialized fields, allowing for character behavior to be adjusted, without the need to updated the scripts.
- Integrated camera movement, particle effects, and quick transitions to provide the player with clear feedback with what is happening.
- Practiced splitting-up mechanics and responsibilities across multiple MonoBehavior C# scripts and components rather than isolating all logic inside a single script.
- Gained experience debugging interactions between different inputs, physics, collision, and scene management, which all typically behave differently when combined than when tested independently.

## Controls

| Input | Action|
| --- | --- |
| A/D | Rotate Character |
| W | Speed Player up when on ground and holding|

## Technologies

- Unity 6 -> Developed using Unity 6000.5.4f1
- C#
- Git
- Github

## Running the Project

1. Clone the repository
2. Open Unity Hub
3. Select Add -> Add project from disk
4. Select the clones project directory.
5. Open the project using the Unity editor version stated above.

## Credits 

The original project was created as part of the "Complete C# Unity 2D Game Development (Updated To Unity 6)" course by GameDev.tv.

Course:
[Udemy Course](https://www.udemy.com/course/unitycourse/?couponCode=MT260907G1A)
