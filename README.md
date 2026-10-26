# Brad Chamberlain

Software developer. Simulation, Blender tooling, small productivity tools, and the C++ and Python tools around them.

## Simulation

- [FluidX3D](https://github.com/meet-brad-ch/FluidX3D) - fork of ProjectPhysX/FluidX3D, lattice
  Boltzmann CFD on OpenCL. Adds a CMake build with one target per example, a Setup API that
  configures a simulation in SI units, SDF-file voxelization and an SDF cache.
- [SDFGenFast](https://github.com/meet-brad-ch/SDFGenFast) - fork of christopherbatty/SDFGen,
  signed distance fields from triangle meshes. Adds a CUDA GPU backend, a multi-threaded CPU
  backend, Python bindings and mesh repair.
- [FlaxEngine](https://github.com/meet-brad-ch/FlaxEngine) - engine fixes found while building a
  paragliding simulator on Flax, submitted upstream as pull requests. Built and tested on Windows
  and Linux.
- [FlaxMCP-upstream](https://github.com/meet-brad-ch/FlaxMCP-upstream) - fork of eXoz00rd/FlaxMCP,
  the MCP server for Flax Engine. Adds a bridge host that survives script reloads, game commands,
  jobs with progress and typed tools for live objects.

## Blender

- [add_curve_sapling](https://github.com/meet-brad-ch/add_curve_sapling) - fork of the Sapling
  Tree Gen extension for Blender 5.2 LTS. Parametric Weber-Penn trees with leaves, pruning, an
  armature rig and wind. 276 headless tests. Source at
  [projects.blender.org](https://projects.blender.org/Brad-Chamberlain/add_curve_sapling),
  releases here.

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
