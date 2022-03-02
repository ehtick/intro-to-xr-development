# Physics

**NOTE:** *Might want to delve into certain unity concepts here, such as RigidBody and use these to connect theory with practice. TBD*

## Objectives

- *Objective 1*
- *Objective 2*
- *Objective 3*

## Introduction

In XR, physics play an important role in making the experience as close to the real world as possible. Physics enables objects to be controlled and manipulated by approximating some of the forces in the real world, like gravity. Moreover, certain engines provide the opportunity to give objects values such as mass that allow further physical interactions between them and the environment.

### Gravity

### Forces

Any interaction that modifies or changes the motion of an object is considered a **force**. When a force is applied to an object, it's movement, direction and/or speed are altered. Forces have their own magnitude and direction, which means they can be represented as vectors. Though vectors are mathematical concepts with their own operations and rules, we do not need to go in depth for a basic understanding and usage in XR development.

*[Image showing a force vector]*
`<image>`

Forces can be applied through environment changes, user's input, etc. As an example, applying force in the right direction to an object as the user presses a button, can move the object in that direction provided no other forces are currently acting on its body.

`<image>`

### Pivots

Nonetheless, certain movements (like rotations) require more than just force to occur. This is where the concept of a pivot comes to play. A **pivot** is a (usually central) point, on which an object oscillates or turns. In XR development, a pivot point is an element that is added to objects in order to mimic turning, rotation or oscillation when a force is applied.

`<image>`

Without a pivot point, any force added to an object will result in movement (provided the applied force is greater than any other existing force already acting on the object, like gravity) in the direction of the force. After adding a pivot point however, the application of force may result in turning or oscillation, depending again on the existing forces *and* the direction of the applied force.

`<image>`