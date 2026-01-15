# dev-visual-coding-apps-I-ve-made
visual coding apps you can steal and are open script

## Blender Visual Coder

A node-based visual programming interface inspired by Blender's shader editor. Create visual logic flows by connecting input, output, and processing nodes with draggable connections.

### Features
- **Node System**: Create and arrange nodes (Input, Output, Process, Logic)
- **Socket Connections**: Drag from white dots to create visual connections between nodes
- **Live Canvas Customization**:
  - Change background color in real-time
  - Customize accent color for connections
  - Toggle between grid, dot, or blank background patterns
- **Interactive Canvas**:
  - Drag nodes to reposition
  - Pan canvas with middle mouse or spacebar + drag
  - Right-click nodes to delete
  - Click to select nodes
- **Node Types**:
  - **Input**: Data source nodes with output sockets
  - **Output**: Data sink nodes with input sockets
  - **Process**: Transform nodes with inputs and outputs
  - **Logic**: Conditional nodes
- **Export & Management**: Export your node graph as JSON

### How to Use
1. Open `blinder-visual-coder.html` in any modern web browser
2. Use the "Add Node" buttons to create nodes on the canvas
3. Click white dots on node sockets to start creating connections
4. Click another socket to complete the connection
5. Drag nodes to organize your visual program
6. Customize the canvas background and colors with the control panel
7. Export your graph as JSON for later use

### Controls
- **Add Nodes**: Click buttons in the "Add Node" section
- **Create Connections**: Click on white socket dots to connect nodes
- **Move Nodes**: Drag nodes around the canvas
- **Pan Canvas**: Middle mouse button or Spacebar + drag
- **Delete Nodes**: Right-click on a node
- **Select Nodes**: Left-click on a node

### Technical Details
- Built with vanilla HTML, CSS, and JavaScript
- Canvas-based rendering for smooth performance
- No external dependencies
- Works offline
- Real-time visual feedback for all interactions
- Bezier curve connections for aesthetic node linking

### Inspiration
The visual node editor is inspired by Blender's powerful node-based workflow, allowing developers to create complex logic through visual composition rather than traditional text-based coding.
