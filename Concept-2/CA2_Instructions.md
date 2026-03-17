# CS2053 
## Concept Assignment 2
### Due: 11:59pm, Mar 13, 2026

---

## Instructions

Write your answers in a Markdown file named `CA2_*YourName*.md` and submit via D2L.  
If you include images (for example, in question 7), just submit the photo with the assignment, and note it in your response. 
*Make sure to number your answers to correspond to the questions.*

---

## Questions

**1**: Consider polling and event-based models of handling input.  
**| a**: What is the difference? How are they implemented?  
**| b**: Provide some creative examples of how you would use each.

**2**: The 4 values of “**KeyState**” we defined depend on the states of the keyboard in both the last and current frame.  
**| a**: Describe a situation in game programming which definitely needs to use this 4-value keystate, and a situation in game programming which only needs to depend on the current state of the keyboard.  
**| b**: For each of the four key states, give an example of a game action which would need to be triggered by that keystate.

**3**: Consider the sound emitters and listeners we discussed in class.  
**| a**: In a first-person 3D game, why do we always set the listener’s position to be the same as the camera? For third-person, what are the advantages and problems when we set the sound listener’s position in the same location as the player object?  
**| b**: Describe a situation in a third-person 3D game that, when the sound listener’s position is not properly set, the player object may hear a sound from the left, but the camera may view the sound emitter on the right.

**4**: For each of the following DSP effects: Describe the effect in your own words, then provide an example from a game *[which you played, know, or can imagine]* that uses such an effect.  
- Reverb  
- Pitch shift  
- Compressor  
- Low-pass filter  

**5**: Describe how collision could be calculated between a rectangle and a circle. Give pseudocode of how this would be implemented in a game.

**6**: Considering unprojection as we discussed it in class:  
**| a**: In your own words, explain what unprojection is and what it does in a 3D rendering pipeline. Why can a screen coordinate not directly give us a single 3D point?  
**| b**: Describe three concrete gameplay systems that rely on unprojection and briefly explain how it is used in each case.

**7**: Design a FSM (State Machine) for the behaviour of an AI hockey player. The FSM should have 4 or more states and state transitions between them based on some events. Draw a diagram to represent the potential states of the player. Provide details about the transitions on the arcs between states. 

**8**: Describe the idea and processes of natural selection genetic algorithms. Why would we use these in games? How? When would it not make sense to use them?

**9**: For each of the following pathfinding algorithms: Best-First, Dijkstra, and A*, answer the following questions:  
**| a**: Is the algorithm an exhaustive or a heuristic search algorithm?  
**| b**: Is the algorithm resource (CPU and memory) intensive?  
**| c**: What is a situation that makes sense to use this algorithm?

**10**: Throughout the course Colin and Scott have shared some *cool*/*super* games with unique features and design that exemplify the possibilities of the relevant topics we've covered.

Tell us about a game of your choice that does something unique or special around one of the game elements we've talked about in the course!
+ *If you don't play games, that's okay too! Tell us an idea you have of how a game could do something unique with some of the topics we've covered so far!*  

---