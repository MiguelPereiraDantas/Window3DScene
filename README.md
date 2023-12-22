# Multi-Window Three.js Application

This project showcases a multi-window web application using Three.js, where each window is represented by a dynamic cube in a 3D space. The cubes respond in real-time to changes in the positions of the browser windows.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

The application utilizes Three.js to create a dynamic 3D scene where cubes represent individual browser windows. The positions and sizes of these cubes are updated in real-time based on changes in the respective window positions.

## Prerequisites

Ensure you have the following prerequisite installed:

- [Three.js Library](https://threejs.org/): Download and include the Three.js library in your project. You can find the library in the `three.r124.min.js` file.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/MiguelPereiraDantas/Window3DScene.git
   ```
Include the Three.js library in your HTML file:
``` html
<script type="text/javascript" src="path/to/three.r124.min.js"></script>
```
## Features

1. Multi-Window Support: The application utilizes the WindowManager class to manage and synchronize information about multiple browser windows or tabs.

2. Dynamic Cube Positioning: Cubes in the 3D scene dynamically respond to changes in the positions of their corresponding browser windows.

3. Custom Metadata: Each window instance supports custom metadata, providing flexibility for additional information storage.

## Folder Structure

```lua
/
|-- index.html
|-- main.js
|-- WindowManager.js
|-- three.r124.min.js
|-- style.css
|-- README.md
|-- LICENSE
```

- index.html: Main HTML file.
- main.js: Main JavaScript file containing the Three.js application logic.
- WindowManager.js: JavaScript module defining the WindowManager class for managing window information.
- three.r124.min.js: Three.js library (version r124).
- style.css: CSS file for basic styling.
- README.md: Project documentation.
- LICENSE: License information.

## Usage

Open the application in multiple browser windows or tabs to witness the dynamic response of the cubes to changes in window positions.

## Configuration

No additional configuration is required. Customize the application behavior through the WindowManager class.

## Dependencies

- [Three.js] (Version r124)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- The project utilizes the Three.js library for 3D graphics.
- Special thanks to the open-source community for contributions and support.
