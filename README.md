# exercise17
README
Image Editor – Windows Forms (C#)

This project is a simple Windows Forms application written in C#. It allows users to load, view, and save images. The user interface is created using Visual Studio Toolbox components, and the application logic is implemented in the code-behind file.

Features
Select Image

Opens an OpenFileDialog.

Allows the user to choose an image (JPG, PNG, BMP, etc.).

Displays the selected image inside a PictureBox.

Save Image

Opens a SaveFileDialog.

Saves the currently loaded image from the PictureBox.

Supports multiple output formats such as PNG or JPG.

Exit Application

Closes the program safely using Application.Exit().

Requirements

Visual Studio 2019 or newer.

.NET Framework 4.x or .NET 6/7 Windows Forms.

A form containing the following Toolbox controls:

PictureBox

Button for selecting an image

Button for saving the image

Button for exiting the application

The control names in the form should match the names used in the code, such as PictureBox1, btnSelectImage, btnSaveImage, and btnExit.

How It Works

The user clicks the Select Image button.
The selected image is displayed in the PictureBox.

The user clicks the Save Image button.
A dialog appears to choose the save location, and the image is saved.

The user clicks the Exit button.
The application closes.

Notes

If no image is selected, the Save Image button will show an error message.

The application saves only the image currently displayed in the PictureBox.

PictureBox.SizeMode should be adjusted for best display (Zoom is recommended).
