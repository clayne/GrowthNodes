Windows compiled version available: https://github.com/hsab/GrowthNodes/releases/tag/v0.3.0

This branch will likely not be maintained. Please refer to master. What you see below is the proposal I wrote before developing the addon. Special thanks to [Jacques Lucke](https://twitter.com/jacqueslucke?lang=en) whose addon, [Animation Nodes](https://github.com/JacquesLucke/animation_nodes), was inspirational in how I approached user interactivity and data management in GrowthNodes.

# UMOG: Unified Model of Organic Growth
A Blender plugin for generative content creation and simulation of organic growth processes. Inspired by Computational Growth by Deskriptiv and Wanderers by Mediated Matter. 

Introduction:
-------------
This project aims to create a plugin for an existing 3D software suit, namely [Blender.](https://en.wikipedia.org/wiki/Blender_(software)) The plugin would allow users to replicate a wide variety of organic structures occurring in nature using a unified mathematical model. The unified model itself is a collection of different subsystems such as those listed below while allowing the user to add their own system as well:

*   Rules-Based System and Equation-Based System
*   Finite Difference Scheme and Cellular Automata
*   Cellular Automata for Reaction-Diffusion Systems
*   Cellular Automata for the Wave Equation

Our project aims to be versatile and out-reaching allowing the user to create structures that are dynamically generated with resemblance to [real-life phenomenon](https://en.wikipedia.org/wiki/Patterns_in_nature) such as Coral Reefs, Bacteria, Crystals, Trees, Branches, Flowers, etc.

Technicalities:
--------------
Implementation and algorithms will be heavily inspired by chapter 18 of [Handbook of Bioinspired Algorithms and Applications](https://www.crcpress.com/Handbook-of-Bioinspired-Algorithms-and-Applications/Olariu-Zomaya/p/book/9781584884750) and will utilize complex preexisting libraries and functionalities available in Blender, such as [Dynamic Topology](https://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.66/Dynamic_Topology_Sculpting) ([Paper 1](http://www.sciencedirect.com/science/article/pii/S0097849311000720) / [Paper 2](https://farsthary.files.wordpress.com/2011/10/dynamic-subdivision-sculpting-final.pdf)) and native [Sculpting](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/index.html)functionalities and APIs.

We are hoping to implement the UI using Blender's existing node system, [PyNodes](https://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.67/Python_Nodes), to allow for visual programming. However the feasibility and possibility of this needs to be analyzed in relation to UI/UX and ease of use.

Inspiration
-----------
This project was inspired by a [video](https://www.youtube.com/watch?v=9HI8FerKr6Q) released by [deskriptiv](http://www.deskriptiv.de/) in collaboration with [Mediated Matter Group](http://matter.media.mit.edu/) at MIT investigating the possibilities of [Wearables for Interplanetary Travels](https://www.behance.net/gallery/21605971/Neri-Oxman-Wanderers).
