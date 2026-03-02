# CS 330 - Computational Graphics and Visualization Portfolio

## Project Overview
This repository contains my final project for CS 330, demonstrating competency in 3D graphics programming using OpenGL and C++. The project consists of a fully realized 3D desk scene featuring textured objects, dynamic lighting, and interactive camera navigation.

## Contents
- **7-1_FinalProjectMilestones** - Complete 3D scene with source code and executable
- **FinalProject_DesignDecisions.docx** - Detailed explanation of design choices and implementation

## Project Reflection

### How do I approach designing software?

Throughout this project, I developed new design skills in spatial reasoning and visual composition for 3D environments. Working with computational graphics required me to think about object decomposition—breaking down complex real-world objects into basic geometric primitives like cylinders, cones, and boxes. I learned to visualize how transformations (scale, rotation, translation) could be combined to position and orient shapes to create cohesive compound objects like my desk lamp.

My design process followed an iterative, milestone-based approach. I started by identifying the basic shapes needed for each object, then progressively added transformations, textures, materials, and lighting. This modular approach allowed me to test each component individually before integrating them into the complete scene. I created design sketches and planned my object hierarchy before writing code, which helped me anticipate potential issues and structure my implementation effectively.

The tactics from this design approach—particularly modular development and incremental testing—are directly applicable to future software projects. Breaking complex systems into manageable components, testing each piece independently, and integrating gradually reduces debugging complexity and makes it easier to isolate and fix issues. This principle applies whether I'm building a 3D scene, a web application, or any other software system.

### How do I approach developing programs?

While working on my 3D scene, I employed several new development strategies that enhanced my programming capabilities. I learned to work with external libraries (GLFW, GLEW, GLM) and understand their documentation to leverage existing functionality rather than building everything from scratch. I also developed skills in shader programming and understanding the graphics pipeline—how vertex data flows through transformation matrices to eventually become pixels on screen.

Iteration was fundamental to my development process. Each milestone built upon the previous one, allowing me to refine and expand my work progressively. For example, I initially created basic shapes with solid colors, then added textures, then implemented materials that interact with lighting. This iterative approach meant that when I encountered issues, I could often trace them back to recent changes rather than debugging an entire complex system at once. Each iteration also provided opportunities to improve code organization and refactor for better maintainability.

My approach to developing code evolved significantly throughout the milestones. Initially, I focused on getting individual features working, sometimes with less attention to code structure. As the project grew more complex, I recognized the value of modular functions and clear separation of concerns. I developed custom functions like `LoadSceneTextures()`, `DefineObjectMaterials()`, `SetupSceneLights()`, and `SetTransformations()` that encapsulated specific functionality and made the code more readable and maintainable. By the project's completion, I was thinking more carefully about code architecture and reusability from the start, rather than refactoring later.

### How can computer science help me in reaching my goals?

Computational graphics and visualizations provide knowledge and skills that significantly expand my educational pathway options. Understanding how 3D graphics systems work gives me insight into a fundamental aspect of modern computing that underlies many applications—from scientific visualization to virtual reality. The mathematical foundations I've developed, particularly with transformation matrices and coordinate systems, apply to many other areas of computer science including robotics, computer vision, and physics simulations. These skills make me better equipped for advanced courses in game development, simulation, human-computer interaction, and related fields.

From a professional perspective, computational graphics skills open doors to multiple career paths. The most obvious is game development, where the object modeling, texturing, and lighting techniques I've learned form the basis for creating game assets and environments. However, these skills also apply to many other industries: architectural visualization, medical imaging, data visualization for business intelligence, augmented and virtual reality development, film and animation production, and scientific visualization for research. Even in roles that don't directly involve graphics programming, the problem-solving approaches I've developed—breaking down complex visual problems into manageable components, understanding coordinate systems and transformations, and optimizing performance—are valuable in any technical position.

Perhaps most importantly, this project taught me that I can learn complex, unfamiliar technical domains through systematic study and iterative practice. The confidence gained from successfully implementing a complete 3D graphics system from basic principles will serve me well when facing other challenging technical problems in my career.

## Technical Skills Demonstrated
- C++ programming with OpenGL
- 3D object modeling using primitive shapes
- Texture mapping and UV coordinate systems
- Phong lighting model implementation
- Camera navigation and projection systems (perspective and orthographic)
- Material properties and shader interactions
- Modular code design and best practices

## Future Enhancements
- Add shadow mapping for more realistic lighting
- Implement more complex materials (reflection, refraction)
- Add animation capabilities for moving objects
- Expand scene complexity with additional objects
- Optimize rendering performance for larger scenes
