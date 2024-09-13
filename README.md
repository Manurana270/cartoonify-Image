# cartoonify-Image
This is a graphical user interface (GUI) application built using Python, OpenCV, and Tkinter. The application allows users to upload images, apply cartoon effects using bilateral filtering and adaptive thresholding, and save the processed images. The GUI is designed to be simple and user-friendly.

Features
Upload Images: Users can easily upload images through a file explorer.
Apply Cartoon Effect: The app processes images using OpenCV to apply cartoon-like effects.
Preview Images: Users can preview the original image alongside the cartoonized output.
Save Images: Users can save the final cartoonized images to a desired location.
User-Friendly Interface: The interface is intuitive and built using Tkinter.
Installation
To install and run the application, make sure you have Python installed, and use the following command to install required dependencies:

pip install opencv-python easygui numpy imageio matplotlib Pillow
How to Run
Clone or download the project files.
Navigate to the project directory.
Run the script:
python main.py
This will launch the GUI, where you can upload an image, apply the cartoon effect, and save the processed image.

How It Works
Image Upload: The user can upload an image through a file selection dialog.
Processing Steps:
Convert the uploaded image to grayscale.
Smooth the grayscale image to reduce noise.
Detect edges in the smoothed image using adaptive thresholding.
Apply a bilateral filter to smooth and preserve edges in the original image.
Combine the edges with the filtered image to create the final cartoon effect.
Save Feature: After cartoonizing the image, the user can save the processed image with a custom name.
Application Workflow
Select an Image: Click the "Cartoonify an Image" button to browse and upload an image.
Cartoonize: The image is processed, and the cartoon effect is applied.
Save: After previewing the cartoonized image, save it to your local system.
Example Output
Original Image:
Cartoonized Image:

This README provides all necessary details about the application without including code snippets. Let me know if you'd like to customize it further!






