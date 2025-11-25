[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# icon-tags
Tags for the iconography of the Byzantine seal - developed in the framwork of the ANR-DFG DigiByzSeal project - for making the main iconographic features searchable on SigiDoc editions.
A web tool for selecting standardised iconographic tags for Byzantine seals.  
This selector is designed to support SigiDoc-based scholarly editions by providing a consistent and searchable vocabulary for the main iconographic features.

## What this tool does

- Displays all iconographic categories defined in the project.
- Offers multi-selection within each category (simple click, no need for Ctrl/Cmd).
- Automatically compiles all selected elements into a single line of text.
- Produces a space-separated tag string ready for insertion into SigiDoc XML editions ( <figDesc ana="">).
- Includes individual reset buttons for each category and a global reset option.
- Allows direct copy-to-clipboard of the generated tag string.

## About the nature of the tags

This instrument **is not intended to provide a full or exhaustive iconographic description** of the iconography.  
It only offers a set of **structured but non-hierarchical keywords** designed to facilitate searchability.

- These tags **must not be interpreted as expressing any hierarchy**, importance, or sequence.  
- The conceptual model is that of a **flat hierarchy**: each tag is an independent descriptor, without internal ranking or dependency.

The purpose is pragmatic: to enable efficient indexing and retrieval in SigiDoc editions, not to model the entire complexity of Byzantine sigillographic iconography.

The tool is available online here:

**https://sigidoc.github.io/icon-tags/**
