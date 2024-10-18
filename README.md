# Autism Detection System

## Introduction

The Autism Detection System is an advanced web application that utilizes machine learning algorithms to analyze facial features and detect potential signs of autism. This non-invasive method provides quick and accurate results, aiming to support early diagnosis and intervention.

Key Features:
- Real-time face detection and tracking
- Instant autism classification
- User-friendly interface
- Privacy-focused (no data storage)

## Installation

Follow these steps to set up the Autism Detection System on your local machine.

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/autism-detection-system.git
cd autism-detection-system
```

### Step 2: Create a Virtual Environment

#### On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS and Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies

With the virtual environment activated, install the required packages:

```bash
pip install -r requirements.txt
```

## Running the Application

1. Ensure you're in the project directory and your virtual environment is activated.

2. Start the Flask application:
   ```bash
   python app.py
   ```

3. Open a web browser and navigate to `http://127.0.0.1:5000/`

4. You should see the home page of the Autism Detection System. Click on "Start Test" to begin using the application.

## Usage

1. On the test page, allow the application to access your camera when prompted.
2. Position yourself in front of the camera, ensuring your face is clearly visible.
3. The system will automatically detect your face and begin the analysis.
4. Once complete, the result will be displayed on the screen.

## Troubleshooting

- If you encounter any issues with camera access, ensure that your browser has permission to use the camera.
- For any dependency-related errors, make sure you've correctly activated the virtual environment and installed all required packages.

## Contributing

We welcome contributions to the Autism Detection System! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please don't hesitate to reach out:

- Email: fitsumgetachewtola@gmail.com
- GitHub Issues: [https://github.com/fitsumgetachew/AutismDetection/issues](https://github.com/fitsumgetachew/AutismDetection/issues)

Thank you for your interest in the Autism Detection System!
