# CS2053 
## Concept Assignment 3
### Due: 11:59pm, Mar 30, 2026

---

## Instructions

Write your answers in a Markdown file named `CA3_*YourName*.md` and submit via D2L.  
If you include images, just submit the photo with the assignment, and note it in your response.
*Make sure to number your answers to correspond to the questions.*

---

## Questions

**1**:
Describe the role of the **User Interface** in games.
How does this **differ** from **User Experience**? 
How do they work **together**?

**2**:
Consider the difference between **programming languages** and **scripting languages** in game development.

**| a**: Briefly explain the differences between them. 
**| b**: Imagine you are developing a moderately complex game *(your choice of genre)*. Describe a part of the game that would make sense to implement using a **programming language**, and one part that would make sense to implement using a **scripting language**. Explain why for each choice.

**3**: 
Regarding this *SCUMM-ish* psuedocode:
```
actor Manny
actor Glottis

Glottis.say("Manny-boy! How are we gonna get home?")

if player._has("NumberNineTicket")
    Manny.say("Ah yes... premium travel.")
else
    Manny.say("Sorry, no ticket, no ride.")
end
```
**| a**: Describe (in english) the rules you would write to tokenize this. *(define breakpoints, keywords, etc)*
**| b**: List the tokens that would result from your rules.

**4**:
In a multiplayer game, player usernames must follow these rules:
- Must start with a letter
- May contain letters, numbers, or underscores
- Must be between **4 and 12 characters long**
**| a**: Write a **regular expression** that matches valid usernames.
**| b**: For each of the following names, state whether it would match your regex.
- xX_Ji-Ji_Xx
- 3Stacks4lyfe
- b0b
- memegod_67
- MartianDiplomat
- i1liil1

**5**:
Consider the following simple grammar for arithmetic expressions:

```
<integer>    ::= [0-9]+
<expression> ::= <expression> "+" <expression>
               | <expression> "-" <expression>
               | <integer>
```

Using this grammar, create an **AST** for the expression: `7 + 5 + 3 - 2`

**6**: 
A developer is designing the save system for an RPG where saves may contain:
- player inventory
- world state
- NPC positions
- quest progress
**| a**: Describe one advantage and disadvantage of using a **text-based format**.
**| b**: Describe one advantage and disadvantage of using a **binary format**.
**| c**: What would you do? Explain why.

**7**:
In a multiplayer game, clients send their position to the server every frame.
Some players modify their game client to send fake positions and teleport across the map.
**| a**: What type of cheating is this? How is it possible?
**| b**: How could you, as a developer, attempt to prevent this.

**8**:
Consider the narrative elements and structures we talked about in class (Hero's journey, Freytag's Five-Act, etc.) 
**| a**: Tell me about a game you've played which follows one of these structures. Which one? How so?
**| b**: How does this game's narratology tie in with it's ludology? Any ludonarrative dissonance? Does gameplay affect the narrative in any way?

**9**: 
You are a game developer.
You're making a game and you want to create a feeling of **moral tension** and **stress under time pressure**.
Considering the **MDA** (Mechanics, Dynamics, Aesthetics) framework,
Describe the following and their **design characteristics**: 
**| a**: Some creative **mechanics** that you could create to support this goal
**| b**: The **dynamics** that would emerge from them
**| c**: The intended resulting **aesthetic** experience

**10**:
The key game experience concepts of **immersion** and **embodiment** often get confused. Explain each and the distinction in your own words, providing some examples *(other than those we talked about in class)* for each.


---