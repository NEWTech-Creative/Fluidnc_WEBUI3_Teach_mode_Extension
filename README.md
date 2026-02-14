![Licence: CC BY-NC 4.0](https://img.shields.io/badge/Licence-CC%20BY--NC%204.0-lightgrey.svg)

\# Teach Mode for FluidNC WebUI 3



Teach Mode is an extension specifically for \*\*FluidNC WebUI 3\*\*. It is designed for use cases where you want to \*\*create set points or generate G-code by physically jogging the machine\*\* (Teach Mode), rather than building toolpaths in CAD/CAM software.



This is ideal for machines where \*\*on-the-fly set points\*\* are needed and where real-world positioning is easier than software setup, such as:



\- Camera sliders

\- Robotic arms

\- Custom automation rigs

\- Any machine where positions must be captured from the real world



\## What it does



Teach Mode allows you to:



\- Capture \*\*unlimited lines\*\* of set points

\- Store positions for \*\*up to 6 axes total\*\* (e.g. X Y Z A B C)

\- Control \*\*point-to-point speed\*\* (feedrate) per move

\- Add \*\*additional G-code entries\*\* for controlling other devices (e.g. triggers, IO, waits)

\- \*\*Edit on the fly\*\* (adjust, reorder, insert, delete)



\## Storage and reliability



\- Save and load projects from the device’s \*\*local SD card\*\*

\- Automatic project storage helps ensure you can keep working confidently, even after a restart

\- Designed to reduce data loss risk if the machine or UI restarts unexpectedly



\## Compatibility



\- \*\*FluidNC WebUI 3\*\*

\- Works with machines configured for up to \*\*6 axes\*\* (depending on your FluidNC setup)



\## Installation



> Coming soon.



(Planned: copy the extension into the WebUI 3 extensions folder / install via the recommended WebUI 3 extension method.)



\## Usage



## Main Interface
![Main Interface](dist/Slider%20extension.png)

## Setup 1
![Setup in Extensions](dist/Slider%20extension%20setup%201.png)

## Setup 2
![Setup in Extensions](dist/Slider%20extension%20setup%202.png)


Basic flow (high level):

1\. Jog the machine to a position

2\. Capture the point (axes + feedrate)

3\. Repeat to build a sequence

4\. Optionally add extra G-code lines (IO, dwell, triggers)

5\. Save to SD / replay / export as G-code



\## Roadmap



\- \[ ] Installation instructions aligned with FluidNC WebUI 3 extension system

\- \[ ] Export to `.nc` / `.gcode`

\- \[ ] Per-line metadata (labels/notes)

\- \[ ] Reorder points via drag-and-drop (optional)

\- \[ ] Safer startup and end macros (optional)



\## Contributing



Pull requests are welcome. If you’re proposing changes, include:

\- A short description of the use case

\- Screenshots (if UI-related)

\- Notes on any WebUI 3 / FluidNC assumptions



\## Licence

This project is licensed under:

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**  
https://creativecommons.org/licenses/by-nc/4.0/

This licence allows:

- Use  
- Modification  
- Sharing  
- Forking  

**Commercial use and resale are not permitted.**


