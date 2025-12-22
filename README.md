# CS-330-Comp-Graphics-and-Visualization




This repository contains the final project for CS 330: Computational Graphics and Visualization. The goal of this project was to construct a complex 3D scene using C++ and OpenGL, demonstrating an understanding of meshes, lighting, textures, and 3D navigation.

For my scene, I chose to replicate a modern desktop "battlestation." I am personally obsessed with clean desk setups and am constantly shifting my own gear around in real life to find that perfect aesthetic, so building a virtual version felt like a natural choice. The scene features a custom mechanical keyboard, a laptop workstation, a coffee mug, and a mouse, all rendered on a wood-grain desk with dramatic lighting.

Reflection
How do I approach designing software?
When it comes to design, I usually start with a strong visual goal in my head before I write a single line of code. For this project, I didn't just want to place random shapes; I wanted to create a mood. I envisioned a dark, sleek setup with cool cyberpunk lighting. This guided every choice I made, from the textures I picked to the specific way I angled the desk.

This project really helped me refine my ability to break complex objects down into simple parts. I realized that a complex laptop is really just two flat boxes, and a coffee mug is just a cylinder with a smaller box for a handle. Learning to see the simple geometry inside complex real world objects is a design skill I will definitely use moving forward. My process was very iterative. I would place an object, run the code, see that it was floating an inch off the table, and then go back and tweak the math. It taught me that design isn't just about the big picture but about the tiny details that make a scene feel grounded and real.

How do I approach developing programs?
My development strategy for this 3D scene shifted towards modularity very quickly. Early on, I realized that writing out the math for position, rotation, and scale for every single key on the keyboard would be a nightmare. So, I wrote custom helper functions like SetTransformations to handle the heavy lifting. This let me focus on placing the objects rather than getting lost in the matrix math every time.

Iteration was the biggest factor in my success here. I hit a major wall where my lighting wasn't showing up because my black textures were absorbing all the color. It took a lot of trial and error, adjusting the ambient light and material shininess, to finally get that "glossy plastic" look where the lights actually reflected off the keys. I evolved from just trying to get code to compile to actually understanding how the shader physics worked. By the end, I wasn't just guessing numbers; I was tuning material properties to get the specific look I wanted.

How can computer science help me in reaching my goals?
Computer science is often about data structures and algorithms, but this course showed me the visual side of programming. Understanding how to manipulate 3D space and render graphics gives me a huge advantage in any field that involves user interaction. Whether I go into game development, simulation, or even standard UI design, knowing what happens "under the hood" of the graphics pipeline helps me build better, more responsive software.

Professionally, this project gave me a lot of confidence in C++. Working with low level libraries like OpenGL forces you to manage your own memory and pointers carefully, which makes you a stronger programmer overall. Plus, having a visually impressive 3D project in my portfolio shows future employers that I can tackle complex math and physics concepts and turn them into something tangible and creative.
