# Project-3: PNG to JPG Converter

## Description
This project provides a graphical interface for converting PNG images to JPG format. Users can select a PNG file, preview it, and convert it to a JPG file with a single click.

## Prerequisites
Before running this project, ensure the following modules are installed:

- **Tkinter**: Included by default in most Python installations.
- **Pillow**: You can install it using pip:

    ```bash
    pip install pillow
    ```

## How to Run
1. Open a terminal or command prompt in the project directory.

2. Run the Python script:

    ```bash
    python project-3.py
    ```

3. The GUI window will open. Follow these steps:
   - Click "Open Image" to select a PNG file.
   - The selected image will be displayed in the preview area.
   - Click "Convert to JPG" to save the image in JPG format.

## Features
- **Image Selection**: Allows users to select a PNG file from their local filesystem.
- **Image Preview**: Displays a preview of the selected PNG file.
- **JPG Conversion**: Converts the selected PNG file to JPG format.
- **Error Handling**: Ensures images with RGBA mode are converted to RGB before saving.

## Limitations
- Supports only PNG files for input.
- Output is saved in the same directory as the input file with the same name but a `.jpg` extension.

## Future Enhancements
- Add support for batch image conversion.
- Allow customization of the output directory and filename.
- Include support for other image formats (e.g., BMP, TIFF).
- Enhance the GUI with modern styling and user experience improvements.

## License
This project is licensed under the MIT License by DzarelDeveloper. Feel free to use, modify, and distribute it as you wish.

---
If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the [project repository](https://github.com/DzarelDeveloper).

