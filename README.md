# Plantation-segmentation-gradio.
Consist a ml model based on automated land vegetation mapping using image processing and interactive visualization.

Land Vegetation Mapping
Overview
This project provides an easy-to-use tool for analyzing land images to detect barren regions, balanced vegetation, and overgrown vegetation using image processing techniques. It uses OpenCV for the backend processing and Gradio to provide an interactive demo interface.

Features:
Automated Detection — Accurately segments land images into barren (plantation needed), healthy, and overgrown vegetation regions.

Interactive Interface — Visualizes the detection and allows users to click on processed images to measure distances from the bottom (useful for further mapping or planning purposes).

Easy Deployment — Gradio-powered demo means you can run the tool and try it in the browser locally.

Getting Started

Requirements:
-Python 3.x
-OpenCV (opencv-python)
-Gradio
-NumPy
-Pillow

Install all the dependencies
Run the program

Upload any land/terrain image using the interface.
View the color-coded output:
Red: Barren/dry soil (needs plantation)
Green: Balanced and healthy vegetation
Blue: Overgrown vegetation

Click on any point to see the measured distance (in pixels) from the bottom of the image.

Future Work:
Integrate with self-driven robotic vehicles for automated plantation.
Export results with geo-coordinates.
Add more refined vegetation classes or improve detection accuracy.

