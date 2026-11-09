---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

Most of my software is open source on [GitHub](https://github.com/JKRT).

## Modeling and simulation

* **[OMJL (OM.jl)](https://github.com/JKRT/OM.jl)**: a Modelica environment written in Julia. It translates Modelica models (equation-based, object-oriented descriptions of physical and cyber-physical systems) into Julia code and simulates them, including models whose structure changes during simulation. It builds on the OpenModelica frontend and works with the Modelica Standard Library. I am the lead developer.
* **[OpenModelica](https://github.com/OpenModelica)**: the open-source Modelica environment of the Open Source Modelica Consortium (OSMC). Modelica is an equation-based language for modeling complex physical systems; OpenModelica provides the compiler (OMC), simulation runtime, editors and libraries for it. I contribute to the compiler and tooling.
* **[EarthSystemClimateInterpretableModel.jl](https://github.com/JKRT/EarthSystemClimateInterpretableModel.jl)**: a global climate model that simulates the development of the Earth's climate and global warming from 1850 to 2500.

## AI-assisted development

* **[JJMCP](https://github.com/JKRT/JJMCP)**: an MCP server written in C++ for agentic Julia programming on macOS and Linux, for working with multiple interactive Julia sessions.
* **[JBOT.el](https://github.com/JKRT/JBOT.el)**: an agentic interface for working with local AI agents in Emacs.

## Smaller Julia packages and examples

* **[ExportAll.jl](https://github.com/JKRT/ExportAll.jl)**: exports all symbols of a Julia module.
* **[Common-Dataflow-Analysis](https://github.com/JKRT/Common-Dataflow-Analysis)**: common dataflow analysis passes in Julia.
* **[LLVMPasses](https://github.com/JKRT/LLVMPasses)**: a minimal example of running LLVM module and function passes.
* **[TDDD55_Tutorial_Code](https://github.com/JKRT/TDDD55_Tutorial_Code)**: examples for the course TDDD55, Compilers and Interpreters.
