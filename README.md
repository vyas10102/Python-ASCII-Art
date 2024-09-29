# Python-ASCII-Art
202403_Intro to Computer Vision_CSCI_6527_10_Project 2

### Authors:

Aditi Vyas (GW ID: G40802010)
Ritwika Das (GW ID: G30941802)

### Professor:

Robert Pless

## Problem Domain and Project Description

The ASCII Art Generator is designed to convert images into ASCII art using Python and the Pillow library, enabling a transformation of standard images into text-based visuals. The primary goal is to provide a simple yet effective tool for users to generate ASCII representations of pictures. The input to this system is any standard image file (e.g., JPG, PNG), and the output is a text file containing ASCII characters that visually represent the image.

This project is particularly useful for artists, developers, and educators who want to incorporate ASCII art into their work or learning environments. For example, developers might use this tool to generate creative display outputs for console applications, while educators might use it to introduce students to basic concepts in digital image processing and character encoding.

## Approach

### High-Level Strategy

The project employs a straightforward image processing technique that involves resizing the image to a manageable width, converting it to grayscale to simplify pixel intensity analysis, and then mapping each pixel's brightness to a specific ASCII character. This method allows for quick and intuitive transformations of images into ASCII art.

### Data and Tools

The ASCII Art Generator works with image data, utilizing the Pillow library to handle image manipulations. No external datasets are used as inputs are individual images provided by users. The simplicity of using ASCII characters to represent pixel brightness levels reduces the complexity often associated with more intricate image processing algorithms.

### Challenges

One challenge is the selection of ASCII characters that effectively represent various shades of gray, maintaining recognizable representations of the original images. The restricted resolution and grayscale conversion also pose limitations, as they can obscure finer details of the original image.

## Results

The ASCII Art Generator reliably transforms images into their ASCII art equivalents, maintaining a balance between simplicity and recognizability. While this approach does not incorporate advanced image processing techniques like machine learning models, it serves its intended purpose efficiently without the overhead of more complex systems. It is well-suited for educational purposes and simple artistic projects but may require enhancements for high-resolution artworks or applications needing finer detail.

## Tools and Resources

- **Pillow Library**: For image processing tasks.
- **Python**: The programming language used to create the tool.
- **GitHub Repositories**: Inspired by various open-source projects on GitHub that demonstrated basic image manipulation techniques.
- **Stack Overflow**: Provided solutions for specific image processing issues encountered during development.

The project consists of two main Python scripts:

- **ascii_conversion.py**: Contains all the functions needed for the image manipulation processes such as resizing the image to a manageable width, converting it to grayscale, and mapping the grayscale pixels to ASCII characters.

## Acknowledgments

Special thanks to the developers of the Pillow library for maintaining and documenting such a robust tool for image manipulation in Python. This project was inspired by various tutorials and code snippets from both Stack Overflow and GitHub, which provided the foundational knowledge needed to undertake this project.
