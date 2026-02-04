# CS2053 
## Concept Assignment 1
#### Due: Feb 13, 2025 @ 11:59pm

---

## Instructions
Write your answers in the file `CA1_*YourName*.md`
*(don't forget to change the name)* and submit via **D2L**.

---

## Questions
Answer the following questions related to contents of Chapters 1-4 of the “Game Programming Algorithms and Techniques” book, the contents of our lectures, and the activities in the labs.

---

**1**. Provide pseudo-code similar to the pseudo code found in the book (_and slides_) for Pac Man but do it for the first level of classic game **Arkanoid**!
+ See a video of Arkanoid **[HERE](https://www.youtube.com/watch?v=v68SuXDOtkM)** to remind yourself.

**2**. In Godot, describe the difference between the three different event functions: **\_process**, **\_physics_process**, and **\_ready**.

 **a**) What is the **role** of these three functions, **when** can they occur, and in what **order**?

**b**) How do they **relate** to the **game loop**?

**c**) Can we **control** how often each of these functions **occur**, and if so, how?

**3**. In **2D game graphics**, explain why **buffering** is commonly used. + Next, explain a reason why someone might want to **disable** buffering.

**4**. What is the difference between a **tilemap** and a **tileset**?

**5**. Assume two game objects `gameObject1` and `gameObject2` in a **2D game**.

**a**) Assume that ```gameObject1.position``` is at **(2, 2)** and ```gameObject2.position``` is at **(8, 8)**, what is the vector that points from ```gameObject1``` to ```gameObject2```?

 **b**) Write code to calculate direction from ```gameObject1```’s position to ```gameObject2```’s position using vector calculations.
 + *Note that direction must be a **normalized** vector.*

**6**. You are coding a **top-down** 2D game with **stereo** sound. In a cut-scene you are scripting an explosion occurs. You must determine whether to play the sound in the right or left speaker depending on **where** the explosion has occurred relative to the **character**. Describe how you can solve this problem using vector math. *Provide formulas to help explain your answer.*

**7**. Consider the following algorithm of a **Phong Reflection Model**:

```csharp
    // Vector3 N = normal of surface
    // Vector3 eye = position of camera
    // Vector3 pos = position on surface
    // float a = specular power (shininess)
    Vector3 V = Normalize(eye – pos) // FROM surface TO camera
    Vector3 Phong = AmbientColor
    foreach Light light in scene
        if light affects surface
            Vector3 L = Normalize(light.pos – pos)
            Phong += DiffuseColor * DotProduct(N, L)
            Vector3 R = Normalize(Reflect(-L, N)) // Reflect –L about N
            Phong += SpecularColor * pow(DotProduct(R, V), a)
        end
    end
```

**a**) In `Phong += DiffuseColor * DotProduct(N, L)`, what is the meaning of `DotProduct(N, L)`? Why do we need to multiply the value of `DotProduct(N, L)` with **DiffuseColor**? For a **directional** **light** without a light **source** **position**, what is the `L` vector?

**b**) For `Phong += SpecularColor * pow(DotProduct(R, V)`, what is the meaning of DotProduct(R, V)`? Why we need to multiply value of `pow(DotProduct(R, V)` with **SpecularColor**?

**8**. Consider the following vectors:
**$\vec{a}$ = &lt; 3,4,2&gt;**,
**$\vec{b}$ = &lt;6,8,0&gt;**,
and the scalar value: **$s = 2$**

Calculate each of the following:

> **a**) $\vec{a}$ + $\vec{b}$
> **b**) $s$ $\cdot$ $\vec{b}$
> **c**) $\vec{a} \times \vec{b}$
> **d**) $\vec{a}$ $\cdot$ $\vec{b}$

**9**. Create a **world transform matrix** that translates by &lt; 3,4,2&gt; and rotates it **90°** about the x-axis.

**10**. Breifly explain why we filter signals from our **input devices**. What are some ways of filtering both **analog** and **digital** inputs?

---
