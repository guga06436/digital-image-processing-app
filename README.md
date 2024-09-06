# Image Processing Tool

## 🖼️ Overview

This project is an image processing tool that implements various filters for image manipulation. It supports both pontual and correlation filters, allowing users to apply different effects to their images.

## 🛠️ Features

- Support for multiple filter types:
  - Pontual Filters:
    - 🔺 Triangular Filter
    - ⚪⚫ Binarization Filter
  - Correlation Filters:
    - 🌫️ Smoothing Filter
    - 🔲 Border Detection Filter
    - ↔️↕️ Sobel Filter
- Color space options: RGB and YIQ
- Custom kernel support for correlation filters
- Easy-to-use interface with adjustable parameters

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Required libraries: numpy, Pillow (PIL)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/image-processing-tool.git
   ```
2. Install the required dependencies:
   ```
   pip install numpy Pillow
   ```

## 📁 File Structure

- `digital_image_processing.ipynb`: Contains interactive example usage of the image processing tool
- `kernels/`: Directory containing sample kernel files for correlation filters
- `images/`: Directory containing sample image files for pontual and correlation filters