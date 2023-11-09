---
title: Welcome!
date: 2023-11-07
---
---
My name is Gourav Pullela and I am currently an undergraduate studying computer engineering.  Feel free to explore my digital garden!

<a target="_blank" href="./assets/Resume/Gourav-Pullela-Resume.pdf">Resume</a> | [GitHub](https://github.com/gpullela) | [Linkedin](https://www.linkedin.com/in/gourav-pullela/)

## Check out my projects!  
---
- [[IUBSAT]]
- [[CGOL-3D |Conway's Game of Life in 3D]]
- [[HPC-in-RSA|HPC in RSA]]
- [[misc |Others]]

## the rabbit hole
---

>"*We're all mad here.*"
\- Cheshire Cat, *Alice in Wonderland*

```mermaid
graph TB;
A["🕳️🐇"] --> low["Low-level programming languages"] & high["High-level programming languages"] & hw["Hardware Description Languages"];
low --> asm["Assembly language"] & c["C (programming language)"];
c --> omp["OpenMP"] --> cpu["CPU"];
asm --> isa["Instruction Set Architecture"] --> cpu;
high --> py["Python (programming language)"] --> jax["JAX"] & ml["Machine Learning"];
ml --> jax --> cpu & gpu["GPU"] & tpu["TPU"];
cpu & gpu & tpu --> hpc["HPC"];
hw --> v["Verilog"] & sv["System Verilog"] --> fpga["FPGA"];

click low href "./Engineering/low-level-programming-language";
click high href "./Engineering/high-level-programming-language";
click hw href "./Engineering/hardware-description-language";
click asm href "./Engineering/Assembly-language";
click c href "./Engineering/c";
click omp href "./Engineering/OpenMP";
click cpu href "./Engineering/CPU";
click isa href "./Engineering/instruction-set-architecture";
click py href "./Engineering/Python";
click jax href "./Engineering/JAX";
click ml href "./Engineering/Machine-Learning";
click gpu href "./Engineering/GPU";
click tpu href "./Engineering/TPU";
click hpc href "./Engineering/HPC";
click v href "./Engineering/Verilog";
click sv href "./Engineering/System-Verilog";
click fpga href "./Engineering/FPGA";
```

## Watch of the Week 📽️
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/QQ2QOPWZKVc?si=UcXjKbEb8rC90HqQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Learn more about my digital garden
---
You will find that many of the projects have linked notes - that is the beauty of a digital garden (and using Markdown files)!  My notes are written using [Obsidian.md](https://obsidian.md/) and built using [jackyzha0/quartz](https://quartz.jzhao.xyz/), which allows me to display this amazing vault as a website statically using [GitHub Pages](https://pages.github.com/) using a single Github Workflow.  



