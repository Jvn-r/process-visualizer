# Process & File Interaction Visualizer
A visual extension to Wtrace
A Windows-based tool that parses system event logs provided by wtrace and visualizes process-to-file interactions in real time.

## What it does
- Run Wtrace with admin privilege through .bat 
- Parses high-frequency system event logs
- Applies dynamic filtering 
- Streams structured events over WebSockets to HTML UI
- Displays live process activity in a graph based UI

## Why this exists
Built to better understand how processes interact with system resources mainly files beyond application-level abstractions

## Tech
- Wtrace
- Node.js
- JavaScript
- WebSockets
- HTML/CSS
- Batch 

## Wtrace
provides all the low level process and file interaction events for windows
https://github.com/lowleveldesign/wtrace


