# Skeletal Fragility Detection

An AI-powered solution for detecting bone fractures and skeletal fragility using deep learning and computer vision.

## 🌟 Features

- Real-time bone fracture detection from X-ray images
- Support for multiple body parts (Hand, Elbow, Shoulder)
- User-friendly web interface
- High accuracy detection (92.44%)
- Detailed analysis reports
- Batch processing capability

## 🛠️ Tech Stack

- *Frontend:* HTML, CSS, JavaScript
- *Backend:* Python
- *Deep Learning:* TensorFlow/Keras
- *Image Processing:* OpenCV, PIL
- *Web Framework:* Flask
- *Data Analysis:* NumPy, Pandas
- *Visualization:* Matplotlib

## 📋 Requirements

- Python 3.8+
- TensorFlow 2.x
- OpenCV
- Flask
- Other dependencies in requirements.txt

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/skeletal-fragility-detection.git

# Navigate to project directory
cd skeletal-fragility-detection

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```
## 💻 Usage

Start the application:

```bash
python app.py
```

2. Open web browser and go to ```http://localhost:5000```
3. Upload an X-ray image
4. View the detection results and analysis

## 📁 Project Structure
```
Copyskeletal-fragility-detection/
│
├── app/
│   ├── static/
│   ├── templates/
│   └── _init_.py
│
├── models/
│   └── model.h5
│
├── utils/
│   ├── preprocessing.py
│   └── detection.py
│
├── requirements.txt
├── app.py
└── README.md
```

## ⚙️ Configuration
Update config.py with your settings:
```
pythonCopyMODEL_PATH = 'models/model.h5'
UPLOAD_FOLDER = 'uploads'
ALLOWED_EXTENSIONS = {'png', 'jpg', 'jpeg'}
```
## 🎯 Key Features
- Pre-trained CNN model for bone fracture detection
- Real-time image processing
- Automatic report generation
- Multi-class classification
- User-friendly interface
- Comprehensive visualization tools

## 📞 Contact
For any queries:

- Email: ramakrishnareddy524@gmail.com
- Department: Computer Science and Engineering (AI&ML)
- Institution: Vignan Institute of Technology and Science

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.


