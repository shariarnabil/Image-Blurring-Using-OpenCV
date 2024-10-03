# Development of 5 Advanced Image Blurring Algorithms Using OpenCV

This project showcases the development and application of **5 advanced image blurring algorithms** using **OpenCV** in **Python**. The techniques implemented include **Averaging Blur**, **Gaussian Blur**, and **Box Filter Blur**. These algorithms were applied to more than 20+ image processing scenarios, optimizing for enhanced visual clarity and edge preservation. The results are visualized using **Matplotlib** for side-by-side comparison.

## Project Features

- **Image Upload**: Users can upload any image for processing.
- **Blurring Algorithms**:
  - **Averaging Blur** (3x3 and 50x50 kernels)
  - **Gaussian Blur** with different kernel sizes
  - **Box Filter Blur** (3x3 and 50x50 kernels)
- **Matplotlib Display**: Visualizes the original and processed images in a single frame for easy comparison.
- **Optimized Image Processing**: Algorithms applied to 20+ image scenarios for enhanced image clarity and edge sharpness.

## Technology Stack

- **Python**: The programming language used for development.
- **OpenCV**: Core library for image processing and applying blur filters.
- **Matplotlib**: Used for displaying original and processed images.
- **NumPy**: Utilized for array manipulation and image data handling.

## How to Run the Project

### Prerequisites

Make sure you have the following dependencies installed:

- OpenCV: `pip install opencv-python`
- Matplotlib: `pip install matplotlib`
- NumPy: `pip install numpy`

### Steps to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
Navigate to the Project Directory:

bash
Copy code
cd repository-name
Run the Code:

If using Google Colab or Jupyter Notebook, open the notebook (.ipynb file) and execute the cells.
If using a Python script, run the file directly in the terminal:
bash
Copy code
python yourscript.py
Upload an Image when prompted for processing.

View Results: The code will apply various blurring techniques and display the original and blurred images using Matplotlib.




File Structure
bash
Copy code
|-- your-project-directory/
    |-- Untitled17.ipynb       # Main Jupyter Notebook for the project
    |-- README.md              # Project documentation
Key Algorithms
1. Averaging Blur
Applies a smoothing filter to reduce noise by averaging pixel values.
Implemented with a 3x3 and 50x50 kernel for different intensities.
2. Gaussian Blur
Applies a Gaussian smoothing filter, providing a more natural blur effect.
Utilizes different kernel sizes to demonstrate the gradual increase in blur.
3. Box Filter Blur
Similar to Averaging Blur, but uses a box filter to compute the average across the kernel size.
Implemented with both 3x3 and 50x50 kernels.

License
This project is licensed under the MIT License 

Author
Your Name - Md Nabil Shariar
