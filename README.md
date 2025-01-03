# MOA Target Scaler

## Demo

You can try the app [here](https://sickmeme-dubbyea.github.io/flapjacks/final.html).

## Overview

The **MOA Target Scaler** is a web-based tool that allows users to simulate and generate targets at various distances based on **Minute of Angle (MOA)**. This tool is primarily designed for shooting enthusiasts, trainers, and marksmen to visualize how different targets would appear at various distances, adjusted by their MOA size. The tool allows users to create dynamic targets, view them in context, and download images with simulated targets overlaid on customizable backgrounds.

### Key Features:
- **Dynamic Target Generation**: Generate targets of various shapes and sizes based on MOA.
- **Customizable Background**: Upload your own background image or use default hilltop gradient scenery.
- **Target Types**: Circle, square, triangle, and diamond target shapes.
- **MOA Scalability**: Select from a range of MOA values (0.75, 1, 1.5, 2, 3, 4) for scalable targets.
- **Distance Labels**: Toggle on and off the display of distance labels below each target.
- **MOA Labels**: Toggle on and off the display of MOA size labels on the targets.
- **Multiple Targets**: Generate multiple targets across the background without overlap.
- **Custom Range**: Set target distance and maximum range for accurate size scaling.
- **Download Image**: Save the generated targets as a PNG image for use.
- **"Buy Me a Coffee" Link**: Support the development by buying the creator a coffee.

---

## Getting Started

To run this application, you can simply clone the repository or open the `index.html` file in your browser. You don’t need a server, as this is a fully client-side application.

### Prerequisites

You only need a modern web browser (Chrome, Firefox, Safari, etc.) to use this tool. No installation is required.

### Instructions

1. **Set Target Distance & Range**:
   - Enter the reference distance for your targets (in yards).
   - Set the maximum range (yards) up to which the targets can be scaled.

2. **Choose Target Shapes**:
   - Select from the available target shapes: **Circle**, **Triangle**, **Square**, or **Diamond**.

3. **Select MOA Values**:
   - Choose the MOA value that corresponds to the target sizes you want to generate. MOA ranges from 0.75 to 4.

4. **Toggle Labels**:
   - Enable or disable labels for target size (MOA) and distance (yards) as needed.

5. **Background Selection**:
   - Choose a default background image (e.g., BobRoss.jpg, Utah.jpeg, etc.) or upload your own custom background image.
   - The image dimensions will be used as the boundary for all generated targets.

6. **Generate Targets**:
   - Click the "Generate Targets" button to render the targets dynamically on the background.

7. **Download Image**:
   - Once the targets are generated, click "Download Image" to save the target layout as a PNG image.

8. **Buy Me a Coffee**:
   - Support the developer by clicking the "Buy Me a Coffee" button.

---

## Functions

### 1. **Target Generation**
   - Users can generate targets at various distances (based on MOA).
   - The targets are generated dynamically, adjusting their size based on the MOA and target distance.

### 2. **Backgrounds**
   - The application allows for two types of backgrounds:
     - **Default Gradient**: A hilltop-style gradient background.
     - **Custom Image**: Users can upload a background image (e.g., nature, desert, etc.).

### 3. **MOA Scaling**
   - The application computes the size of targets in MOA (minute of angle) at different distances.
   - Users can select multiple MOA values for target sizes, such as 0.75 MOA, 1 MOA, 1.5 MOA, etc.

### 4. **Target Placement**
   - The targets are placed randomly on the screen, and users can adjust the maximum distance range to control target placement.
   - Generated targets are positioned horizontally to avoid overlap when multiple target shapes are selected.

### 5. **Labels**
   - MOA and distance labels can be toggled on/off.
   - Distance labels show the range in yards where the target is placed, while MOA labels show the size of the target in MOA.

### 6. **Image Download**
   - After generating targets, the user can download the result as an image using the **html2canvas** library.

### 7. **Support the Developer**
   - There is a **Buy Me a Coffee** link to support the creator of this tool.

---

## Example Use Cases

- **Shooting Practice**: Visualize and generate target layouts for various distances to practice shooting at specific MOA sizes.
- **Training Sessions**: Trainers can set different targets at various distances and simulate shooting conditions with scaled targets.
- **Marksmanship Evaluation**: Use the tool to measure target sizes at different ranges and MOA values for detailed evaluation.

---

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome, whether it’s fixing bugs, improving functionality, or adding new features.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- **html2canvas**: Used for generating downloadable images.
- **"Buy Me a Coffee"**: For the optional donation link to support the creator.

---

## Contact

For more information, contact the developer at:  
- **GitHub**: [GitHub Profile Link](https://github.com/chawit)

---

Thank you for using the MOA Target Scaler tool!
