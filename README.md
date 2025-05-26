# Rubik's Cube Solver

An interactive Java-based Rubik's Cube simulator and solver that allows you to manipulate and experiment with a virtual 3D Rubik's Cube.

## Features

- 3D visualization of a Rubik's cube
- Interactive cube manipulation with mouse controls
- Support for standard cube notation moves (U, D, F, B, L, R)
- Multiple view angles and rotation options
- Color customization options
- Smooth animation effects
- Demo mode available

## Requirements

- Java Runtime Environment (JRE) 8 or higher
- Java Development Kit (JDK) for compilation

## Installation

1. Clone this repository:
```bash
git clone https://github.com/iSaaC2909/Rubix-Cube-Solver.git
```

2. Navigate to the project directory:
```bash
cd Rubix-Cube-Solver
```

3. Compile the Java file:
```bash
javac Rubiks.java
```

4. Run the application:
```bash
java Rubiks
```

## Usage

### Mouse Controls

- **Left Click + Drag**: Rotate the entire cube
- **Click on faces**: Select and twist cube layers
- **Button Interface**: Use the on-screen buttons for various controls and moves

### Keyboard Controls

The program supports standard Rubik's cube notation:
- U: Upper face clockwise
- D: Down face clockwise
- F: Front face clockwise
- B: Back face clockwise
- L: Left face clockwise
- R: Right face clockwise

Add a prime symbol (') for counterclockwise moves (e.g., U', D', etc.)

### Features

1. **Interactive 3D View**
   - Drag to rotate the cube
   - Multiple viewing angles
   - Perspective adjustments

2. **Move Animation**
   - Smooth layer rotation animations
   - Adjustable animation speed
   - Demo mode for move sequences

3. **Customization**
   - Adjustable colors
   - Multiple display modes
   - Configuration options

## Project Structure

The project consists of a single Java file (`Rubiks.java`) that contains all the necessary code for:
- 3D graphics rendering
- Cube state management
- Move execution and animation
- User input handling
- Interface controls

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

This project is based on the classic Rubik's Cube puzzle invented by Ernő Rubik in 1974. 
