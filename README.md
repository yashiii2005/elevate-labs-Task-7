# Batch Image Resizer with Python and Pillow

## Overview

This script automates resizing of all images within a specified folder. It reads images from an input directory, resizes them to the target dimensions, and saves the resized images to an output directory. It supports common image formats such as JPG, PNG, BMP, GIF, and TIFF.

## Features

- Batch resizes images in a folder
- Supports multiple image formats
- Optionally converts and saves images in a specified format
- Handles errors gracefully, skipping unreadable or unsupported files
- Creates the output folder if it doesn't exist

## Requirements

- Python 3.x
- Pillow library (Python Imaging Library fork)
