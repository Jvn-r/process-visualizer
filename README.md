# Process & File Interaction Visualizer

A Windows-based tool that parses system event logs and visualizes process-to-file interactions in real time.

## What it does
- Parses high-frequency system event logs
- Applies dynamic filtering 
- Streams structured events over WebSockets to HTML UI
- Displays live process activity in a graph based UI

## Why this exists
Built to better understand how processes interact with system resources mainly files beyond application-level abstractions

## Tech
- Node.js
- JavaScript
- WebSockets
- HTML/CSS
- Batch (for admin level execution)

## Wtrace
https://github.com/lowleveldesign/wtrace
