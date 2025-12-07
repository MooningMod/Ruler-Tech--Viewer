# Tech Tree Viewer & Analyzer for 2030
a part of the Intelligence Suite

https://www.youtube.com/watch?v=WDv7UGElNUk

A visual analyzer for SR2030’s full technology tree.

# Overview

This tool parses and visualizes the entire Supreme Ruler 2030 tech tree using a modern PyQt5 interface.
It helps modders and advanced players understand dependencies, total chain costs, effects, and unit unlocks in a clean, interactive way.

The project is part of my broader work on SR2030 tools and will be integrated soon into the Ruler Intelligence Suite.

# Main Features

Two layouts: Year/Grid and Hierarchical (Sugiyama)

Clean node graphics with category colors, icons, effects, and unit unlock badges

Full prerequisite/descendant chain analysis

Automatic cluster detection and background grouping

Tech effect mapping with visual indicators

Unit parsing: cost, class, year, region, and required tech

Fast loading via smart caching

Mini-map for quick navigation

Timeline ruler for year-based trees

# Usage
python tech_tree_analyzer.py

Load your DEFAULT.TTRX and .UNIT files when prompted.
The app generates cache files automatically for faster reloads.

# Why I Built It

The SR2030 tech tree is massive and hard to read in text form.
I wanted a reliable tool to see the entire structure, debug mods, check costs, and visually understand how the flow of technologies evolves.
This analyzer solves that problem and will become a core component of the Ruler Intelligence Suite.
