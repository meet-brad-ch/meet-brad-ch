# Brad Chamberlain

Software developer. Simulation, Blender tooling, small productivity tools, and the C++ and Python tools around them.

## Simulation

- [FluidX3D-API](https://github.com/meet-brad-ch/FluidX3D-API) - a modified version of
  ProjectPhysX/FluidX3D, lattice Boltzmann CFD on OpenCL. Adds a CMake build with one target
  per example, a Setup API in SI units, SDF voxelization and atmospheric convection.
  Releases v3.8-api.N on the FluidX3D base.
- [SDFGenFast](https://github.com/meet-brad-ch/SDFGenFast) - fork of christopherbatty/SDFGen,
  signed distance fields from triangle meshes. Adds a CUDA GPU backend, a multi-threaded CPU
  backend, Python bindings and mesh repair.
- [FlaxEngine](https://github.com/meet-brad-ch/FlaxEngine) - engine fixes found while building a
  paragliding simulator on Flax, submitted upstream as pull requests. Built and tested on Windows
  and Linux.
- [FlaxMCP-Live](https://github.com/meet-brad-ch/FlaxMCP-Live) - MCP server for Flax Engine
  with a live editor bridge, an independent fork of eXoz00rd/FlaxMCP. An AI agent checks,
  compiles, plays and drives the game without manual steps. The bridge stays connected
  through script reloads. Adds jobs with progress, editor events, game commands and an
  agent skill.

## Blender

- [Sapling Tree Gen](https://projects.blender.org/extensions/add_curve_sapling) - maintainer of
  the Blender extension, version 1.0.0 for Blender 5.2 and later. Parametric Weber-Penn trees and
  shrubs with bark, leaves, blossoms, an armature rig and wind. 29 built-in presets, and a tree
  can be edited after it is added. On the
  [Blender Extensions Platform](https://extensions.blender.org/add-ons/sapling-tree-gen/).

## Data and planning

- [polars-talib-fast](https://github.com/meet-brad-ch/polars-talib-fast) - every TA-Lib function
  as a Polars expression, generated from TA-Lib's own metadata.
- [ganttuml](https://github.com/meet-brad-ch/ganttuml) - JSON in, Gantt out. One zero-dependency
  Python file that renders PlantUML Gantt charts with per-person calendars and a critical path.
  On [PyPI](https://pypi.org/project/ganttuml/).

## Productivity

- [Tasketier](https://github.com/meet-brad-ch/Tasketier) - task capture and planning for Windows.
  A global hotkey opens a one-line box. Marks in the text (`@fri @15:30 ! #tag`) set the due day,
  the time, the priority and the tags. Today, Upcoming, Inbox and Done views, a tray icon, one
  local JSON file. The same store has a CLI and an MCP server, with a Claude Code plugin in the repo.
- [Tabuzaur](https://github.com/meet-brad-ch/Tabuzaur) - Chrome extension that keeps the pages
  you work with in collections, built by dragging open tabs. Local only, no network.
- [agenthub](https://github.com/meet-brad-ch/agenthub) - messages between coding agents on one
  machine, for example Codex and Claude Code working on one project in turns. Two commands,
  `send` and `next`; a shared folder holds all the state, with no server. A message wakes its
  recipient at once. Includes an agent skill for Claude Code and Codex and a live view of the
  messages in the browser.

## Developer tools

- [CLion-cpplint-nova](https://github.com/meet-brad-ch/CLion-cpplint-nova) - cpplint plugin for
  CLion Nova, a Kotlin rewrite of itechbear/CLion-cpplint. On the
  [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/28989-cpplint-nova).
- [check_init](https://github.com/meet-brad-ch/check_init) - static analysis for uninitialized
  C, C++ and CUDA declarations. Zero dependencies, no compile_commands.json.
- [Ditto](https://github.com/meet-brad-ch/Ditto) - fork of the Ditto clipboard manager with all
  network code removed, built and released by CI.
- [cmake-build-scripts](https://github.com/meet-brad-ch/cmake-build-scripts) - configure and
  build wrappers for CMake projects on Windows and Linux.
