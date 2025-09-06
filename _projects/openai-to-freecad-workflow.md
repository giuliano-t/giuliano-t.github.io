---
layout: default
title: "Generative AI for CAD: From Natural Language to 3D Models"
stack: "Python, Generative AI, RAG, CAD Automation"
priority: "major"
date: 2025-09-01
github: https://github.com/giuliano-t/openAI-to-freeCAD-workflow
---

## The Vision: Democratizing 3D Design

Complex CAD (technical drawing) software often presents a steep learning curve, creating a barrier between a designer's idea and a digital model. This project explores a new frontier in **language-to-geometry interfaces**, building an automated pipeline that transforms natural language instructions into editable 3D models with fully defined parameters.

| ![Turbine Blade](/assets/images/LPT_Blade_FreeCAD.jpg) | ![Design Lamp](/assets/images/Design_lamp_FreeCAD..png) |
|:------------------------------------------------------:|:-------------------------------------------------------:|
| Low Pressure Turbine Blade                             | Design Lamp                                             |




---

## How It Works: A Prompt-Driven Modeling Pipeline

1. **Instruction Input** — the user provides verbal instructions for a 3D part.  
2. **LLM Interpretation** — an LLM (via OpenAI API) translates these into executable Python code.  
3. **Code Execution** — the script runs in FreeCAD to automatically construct a parametric CAD model.  

![Workflow Diagram](/assets/images/Workflow_Diagram_FreeCAD.png)

---

## Key Features & Innovations

- **Automated Pipeline** — end-to-end workflow from text input to CAD model, orchestrated with **LangChain**.  
- **AI-Powered Error Correction** — a **Retrieval-Augmented Generation (RAG)** component detects and fixes common CAD code errors (e.g., misapplied rotations, bad feature constraints).  
- **Parametric by Design** — outputs are true **parametric CAD models**, not static meshes, making them editable and reusable for design iteration.  

---

## Tech Stack

- **Core AI**: OpenAI API, LangChain  
- **AI Technique**: Retrieval-Augmented Generation (RAG)  
- **CAD Software**: FreeCAD  
- **Language & Environment**: Python  

---

[🔗 View on Github](https://github.com/giuliano-t/openAI-to-freeCAD-workflow)
