---
title: "How to debug Pytorch/Deep Learning in VSCode"
date: 2023-10-05
weight: 4
slug: "debugging-pytorch"
keywords: []
toc: true
tags: ["Coding"]
author: "Andrew Siah"
showToc: true
TocOpen: false
draft: false
hidemeta: false
disableShare: false
---

## Debugging a PyTorch Script in Jupyter Notebook

Here is a [youtube guide video!](https://www.youtube.com/watch?v=xNqQNPu3aIg&t=27s)

Open the Notebook: Open your .ipynb file directly in VSCode.
Insert Breakpoints: In the margin next to the cell numbers, click to set breakpoints.
Start the Jupyter Server: If you haven't already, start the Jupyter server by running a cell.
Run the Cell in Debug Mode: Right-click on the cell with a breakpoint and select "Debug Cell" from the context menu.
The execution will pause at the breakpoint, and you'll be able to:

- Inspect variables and their current state.
- Step through the code using the debug toolbar.
- Evaluate expressions in the debug console.
- Inspecting Variables and Watching Expressions

While the debugger is paused, you can hover over variables to inspect their current state, or use the "Variables" panel to navigate through the available data. The "Watch" panel allows you to evaluate expressions based on the current context.

Additional Debug Features
VSCode's debugging environment provides several useful features:

- Conditional Breakpoints: Set breakpoints to pause only when a certain condition is met.
- Logpoints: Instead of breaking, you can log messages to the console, which is helpful for quick inspections without interrupting execution.
- Hit Count Breakpoints: Configure breakpoints to trigger after being hit a specified number of times.

