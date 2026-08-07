# Tensegrity Visualizer

An interactive 3D visualizer for coordination structures modeled as tensegrities: forms that hold their shape through a balance of compression and continuous tension. Built for the Proof of Coordination protocol's structural-integrity work, it lets you load a structure, put it under pressure, and watch how it holds or gives.

It is exploratory: a test bed for whether tensegrity is a useful lens on coordination structure.

## What it does

A tensegrity is made of struts in compression and cables in tension, prestressed so the whole stands as one. The tool renders that structure in 3D and lets you work with it:

- Load a structure from JSON (nodes, struts, cables, prestress, and tensegrity class), or start from a built-in configuration.
- Adjust global cable pretension and strut compression, the Pressure Lab, and read the resulting Full Tensegrity Health.
- Select and pair elements, and rotate, zoom, and inspect the structure directly in the 3D view.

A JSON schema reference documents the structure format.

## Running it

Open `index.html` in a browser. The page is self-contained.
