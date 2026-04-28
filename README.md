# Routebook-Creator
Making route book creation easy.

Roadbook Creator is an application designed to streamline the creation of rally roadbooks, with a primary focus on automated tulip diagram (bolletje-pijltje) generation.

The system aims to provide a structured and extensible approach to designing rally routes, enabling organizers to efficiently create, manage, and export route instructions with precision and consistency.

⸻

Core Features

Current Functionality

* Tulip diagram generation based on structured input
* Intersection modeling (T-junctions, crossroads, roundabouts, etc.)
* Automatic encoding of standardized roadbook instructions
* Logical sequencing of route steps

⸻

Roadmap

Planned features include:

* Map snippet generation for visual navigation
* Map-based challenges and navigation tasks
* Export engine for generating complete roadbooks (e.g. PDF)
* Route persistence (saving, versioning, reuse)
* Advanced editing and validation tools

⸻

Design Goals

* Efficiency: reduce the time required to build complex rally routes
* Consistency: enforce standardized notation
* Extensibility: enable modular expansion and integrations
* Usability: maintain a balance between simplicity and power

⸻

Conceptual Usage

1. Define a route step
2. Specify the intersection type and geometry
3. Select the intended direction
4. Generate the corresponding tulip instruction
5. Append the instruction to the roadbook

⸻

Installation

Work in progress.
git clone https://github.com/your-username/roadbook-creator.git
cd roadbook-creator
# installation steps to be added

Architecture (Planned)

The system is intended to be structured around the following components:

* Core engine: handles route logic and instruction generation
* Rendering layer: responsible for tulip diagrams and future map visualizations
* Data model: structured representation of routes, steps, and metadata
* Export module: generation of output formats such as PDF

⸻

Contributing

Contributions are welcome, including:

* Feature development
* Performance improvements
* UX/UI enhancements
* Rally-specific validation and logic

⸻

License

MIT License

Copyright (c) 2026 NeoGeneticAlex

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to do so, subject to the
following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

Attribution is appreciated. If you use this software in a public or commercial
project, please consider providing visible credit:

"Roadbook Creator by NeoGeneticAlex"

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

⸻

Vision

Roadbook Creator aims to become a developer-friendly platform for building rally roadbooks, supporting both simple touring routes and complex navigation events with multiple instruction types.
