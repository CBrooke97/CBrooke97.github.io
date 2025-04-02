---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Carter Brooke Portfolio
permalink: /
---

<video width="600" controls loop autoplay muted playsinline>
  <source src="{{ site.url }}{{ site.baseurl }}/assets/Recoil.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

# Project Recoil 

**Group project**: Developed over three months as part of my Programming Apprenticeship at Sumo Digital, in partnership with Sheffield Wednesday. 

- Developed in C++, with shaders in HLSL and Python for tools. 

- Co-developed a deferred renderer, using and modifying a proprietary C++ framework to interface with DirectX 11. 

- Designed and implemented a Render Callback system inspired by Frostbite’s RenderGraph. 

- Developed a GPU-accelerated, wind-driven foliage system. 

- Collaborated with Technical Artists on the Metal Snake implementation. 

- Played by Sheffield Wednesday fans during halftime at home matches. 

I co-developed a **deferred rendering pipeline**, leveraging a **proprietary C++ framework** to interface with DirectX 11 and implementing **custom HLSL shaders**. This demonstrated my ability to **balance performance and quality** while applying strong knowledge of rendering architecture and techniques. 

To improve the rendering pipeline’s flexibility, I designed a **Render Callback system**, allowing rendering commands to be structured into passes and processed as a graph. This modular approach streamlined workflows, reinforced my skills in software architecture, and made rendering more scalable. I helped in porting this system for re-use in another (unannounced) academy project. 

Another key contribution was the **wind-driven foliage system**, where I developed a **GPU-accelerated wind animation** method. By computing wind data on the CPU and applying **vertex shader transformations** with noise variation, I achieved realistic movement while maintaining high performance. I further optimized this by using **instanced rendering** and implementing punch-through transparency to avoid unnecessary forward-pass rendering. 

This project strengthened my ability to integrate technical solutions with artistic goals. Collaborating with Technical Artists, I helped implement the Metal Snake, ensuring a visually compelling result while maintaining performance constraints. Throughout the project, I honed my problem-solving, optimization, and teamwork skills, delivering a polished, high-performance rendering system used in a real-world interactive experience. 

# Unreal Engine 5 - Wave Function Collapse Tool 

<video width="600" controls loop autoplay muted playsinline>
  <source src="{{ site.url }}{{ site.baseurl }}/assets/WaveFunctionCollapse.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

**Solo Project:** Developed and refined over a few weeks as part of my Programming Apprenticeship at Sumo Digital. 

- Developed as a reusable Unreal Engine plugin for seamless integration. 

- Implemented in C++ with functionality exposed to Blueprint. 

- Designed for both design-time and runtime use, offering maximum flexibility. 

- Includes a custom Editor tool and data asset to streamline user workflows. 

As part of my work in **Unreal Engine**, I developed a **procedural generation plugin** using the **Wave Function Collapse algorithm** to create tile-based levels. Built from the ground up, the tool was designed with flexibility in mind, allowing designers and programmers to generate levels both at runtime and within the editor. This project reinforced my ability to architect well-structured, reusable systems while ensuring a user-friendly workflow. 

Performance is a critical consideration in procedural generation, which led me to implement the c**ore functionality in C++** for efficiency. To make the tool more accessible across disciplines, I **exposed the logic to Blueprint via a Blueprint Function Library**, allowing designers to leverage the system without deep coding knowledge. Additionally, I developed a **custom data asset**, enabling users to define tile sets and constraints in a data-driven manner, improving ease of use and scalability. 

This project highlights my expertise in engine programming, tool development, and procedural generation, as well as my ability to create efficient, flexible systems that cater to multiple disciplines. It also demonstrates my understanding of performance optimization, scalable software architecture, and Unreal Engine’s plugin and tooling framework. 

  