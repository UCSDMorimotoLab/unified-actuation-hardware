<h1 align="center">A Unified Continuum Robot Actuation Platform - Hardware</h1>

<p align="center">
  Open-source hardware to help researchers get started with high-DOF robots.<br>
  We focus on continuum robots, but the platform is agnostic to robot type!
</p>

<p align="center">
  <a href="https://ucsdmorimotolab.github.io/unified-actuation/"><b>Project website</b></a>
  &nbsp;·&nbsp;
  <a href="https://drive.google.com/file/d/1_eJ_vQgiMd1IlGs77tz4AiUZTHAcJVn4/view"><b>Full actuation assembly video</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/UCSDMorimotoLab/unified-actuation-software"><b>Looking for software?</b></a>
</p>

---

## What's in this repo

| | |
|---|---|
| [Assembly guide](AssemblyDoc_6-24-2026.pdf) | Step-by-step mechanical assembly instructions (PDF) |
| [Bill of materials](BOM_6-25-2026.xlsx) | Parts list for the actuation system (Excel) |
| [CAD and print files](CAD_and_print_files/) | SolidWorks assemblies and 3D-print files |

The [full actuation assembly video](https://drive.google.com/file/d/1_eJ_vQgiMd1IlGs77tz4AiUZTHAcJVn4/view) walks through the complete build alongside the assembly guide.

## System overview

<p align="center">
  <img src="images/overview_combined.jpg" alt="Left: system overview, an operator at the input device teleoperates the actuation assembly on a serial manipulator over a surgical simulator, driving a TDCR endoscope and a CTR instrument. Right: degrees of freedom, outer yaw, outer pitch and insertion plus actuation-assembly DOFs for a 2-segment TDCR or a 3-tube CTR" width="100%">
</p>

## Design overview

<p align="center">
  <img src="images/module_fig.jpg" alt="Annotated CAD render of the actuation assembly: a rotation module and four translation modules on linear rails, with tendons routed to each module and a central working channel" width="100%">
</p>

<p align="center">
  <em>An example actuation assembly for a TDCR. Modules can be reconfigured to match the robot's design and number of DOFs. A central working channel accommodates cameras, forceps, and other tools.</em>
</p>
