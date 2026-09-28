# Edge Detection Using Sobel, Prewitt and Canny

## 📌 Project Overview

This project demonstrates **edge detection techniques in image processing** using a grayscale image. Three popular edge detection methods are applied and their results are compared:

- **Sobel Edge Detection**
- **Prewitt Edge Detection**
- **Canny Edge Detection**

The original image is first converted to grayscale and then processed using each method to highlight important edges and boundaries.

## 🖼️ Results

The project produces the following outputs:

1. Original Grayscale Image
2. Sobel Edge Detection
3. Prewitt Edge Detection
4. Canny Edge Detection

### Output

![Edge Detection Results](images2.png)

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

## 📂 Project Structure

```text
edge-detection/
│
├── input/
│   └── image.jpg
│
├── output/
│   └── edge_detection_results.png
│
├── images2.png
├── edge_detection.py
└── README.md
```

## 🔍 Edge Detection Methods

### 1. Sobel Edge Detection

The Sobel operator calculates the intensity gradient of an image in the horizontal and vertical directions.

It is useful for detecting edges while also providing information about their direction.

### 2. Prewitt Edge Detection

The Prewitt operator uses convolution kernels to detect horizontal and vertical edges.

It is simple and computationally efficient for basic edge detection tasks.

### 3. Canny Edge Detection

Canny is a multi-stage edge detection algorithm. It generally provides thin and well-defined edges by using:

- Noise reduction
- Gradient calculation
- Non-maximum suppression
- Double thresholding
- Edge tracking by hysteresis

## ⚙️ Installation

Install the required Python libraries:

```bash
pip install opencv-python numpy matplotlib
```

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/edge-detection.git
```

2. Open the project folder:

```bash
cd edge-detection
```

3. Run the Python program:

```bash
python edge_detection.py
```

4. The program will display the original grayscale image and the edge detection results.

## 📊 Comparison

| Method | Main Feature |
|---|---|
| Sobel | Detects horizontal and vertical gradients |
| Prewitt | Simple gradient-based edge detection |
| Canny | Produces thin and well-defined edges |

## 🎯 Applications

Edge detection is commonly used in:

- Image segmentation
- Object detection
- Face and shape recognition
- Computer vision
- Medical image processing
- Feature extraction
- Robotics

## 👩‍💻 Author

**Your Name**

## 📄 License

This project is created for educational and learning purposes.
