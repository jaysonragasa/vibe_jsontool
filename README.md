![alt text](https://raw.githubusercontent.com/jaysonragasa/vibe_jsontool/refs/heads/main/ss1.png)

# JSON Tool — Tree, Editor, Prettifier, & Visualizer

A powerful, browser-based utility for developers to inspect, edit, validate, and visualize JSON data. This tool combines a feature-rich Monaco editor with an interactive tree view and dynamic D3.js-powered visualizations, all in a clean, responsive, dual-pane interface.

## Features

This tool is packed with features designed to streamline your workflow when dealing with JSON data.

### Advanced Editor (Powered by Monaco)
* **Syntax Highlighting:** Professional-grade syntax coloring for clear readability.
* **Real-time Validation:** Instantly validates your JSON as you type and provides clear, descriptive error messages.
* **Auto-Formatting:**
    * **Pretty Print:** Format complex JSON into a human-readable, indented structure.
    * **Compact/Minify:** Compress JSON into a single line for optimized storage or transmission.
* **Word Wrap:** Toggle word wrapping to handle long strings without horizontal scrolling.
* **Core Editor Features:** Includes standard editor functionalities like code folding, bracket matching, and multi-cursor support.

### Interactive Tree View
* **Hierarchical Navigation:** Browse your JSON structure in a collapsible and expandable tree.
* **Node Inspection:** Displays key/item counts for objects and arrays directly in the tree.
* **Editor Sync:** Click a node in the tree to instantly highlight and jump to its corresponding location in the code editor.
* **Live Filtering:** Quickly search and filter nodes by key name to find the data you need.

### Data Visualization (Powered by D3.js)
Transform your JSON data into insightful graphs with two distinct visualization modes:
* **Network Graph:** View your JSON as a dynamic, force-directed graph to understand relationships between nodes.
* **Tree Layout:** Display the data in a clean, hierarchical tree diagram.
* **Interactive Controls:**
    * Zoom and pan for detailed inspection.
    * Drag nodes to rearrange the layout (Network Graph).
    * Toggle the visibility of node values.
    * Enter a fullscreen mode for an immersive view.

### Seamless File & Data Handling
* **Multiple Input Methods:**
    * Paste raw JSON directly into the editor.
    * Open local `.json` or `.txt` files using the file picker.
    * **Drag & Drop** a file directly onto the tree view pane.
* **Export & Share:**
    * **Download:** Save the content of the editor as a `data.json` file.
    * **Copy to Clipboard:** Quickly copy the entire JSON document with a single click.
* **Clear & Reset:** Easily clear the editor to start fresh.

### Modern UI & UX
* **Light & Dark Themes:** Automatically detects your system's preferred theme and allows you to toggle between them. Your preference is saved locally.
* **Responsive Design:** The layout intelligently adapts for use on both desktop and mobile devices.
* **Resizable Panes:** Adjust the width of the tree view and editor panes to suit your needs.
* **Keyboard Shortcuts:**
    * `Ctrl/Cmd + S`: Download the current JSON.
    * `Ctrl/Cmd + Enter`: Apply formatting.
* **Status Notifications:** Get clear feedback for actions like validation, copying, and clearing.

## How to Use

1.  **Open:** Simply open the `index.html` file in any modern web browser.
2.  **Load Data:**
    * Paste your JSON data into the editor on the right.
    * Click the "Open" button to load a local file.
    * Drag and drop a JSON file onto the left pane.
3.  **Explore & Edit:**
    * Use the tree view on the left to navigate the structure.
    * Use the editor on the right to make changes.
    * Use the controls in the header and below the editor to format, validate, copy, or download your data.
4.  **Visualize:**
    * Click "Network Graph" or "Tree Layout" to generate a visual representation of your data.

## Built With

* **HTML5 & CSS3:** For the core structure and styling.
* **Vanilla JavaScript (ES6+):** For all application logic, structured in a clean module pattern.
* **[Monaco Editor](https://microsoft.github.io/monaco-editor/):** The code editor that powers VS Code.
* **[D3.js](https://d3js.org/):** The leading library for data visualization.