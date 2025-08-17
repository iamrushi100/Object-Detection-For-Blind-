# 👁️‍🗨️ Object Detector for Blind People

**Object Detector for Blind People** is a Python-based tool designed to assist visually impaired individuals by detecting objects in their surroundings and providing audio feedback in real-time.

---

## 🌟 Features
- **Real-Time Object Detection**: Utilizes YOLOv5 for fast and accurate object recognition.  
- **Text-to-Speech Integration**: Announces detected objects to provide instant audio feedback.  
- **Customizable Object Classes**: Detect only the objects relevant to your needs (e.g., people, bottles, etc.).  
- **User-Friendly Interface**: Simplified design to ensure accessibility for all users.  

---

## 🛠️ Installation

### 1. Install Python
Ensure **Python 3.8+** is installed on your system. You can download it [here](https://www.python.org/downloads/).

### 2. Clone the Repository
bash
```
git clone https://github.com/your-username/ObjectDetectorForBlind.git
cd ObjectDetectorForBlind
```


### 3. Create and Activate a Virtual Environment
```
python -m venv env
# For macOS/Linux
source env/bin/activate
# For Windows
env\Scripts\activate
```
### 4. Install Dependencies  
Install the required Python libraries:  
```
bash
pip install torch torchvision pyttsx3 opencv-python-headless numpy
```

### 3. Interact
The application will:  
- Detect objects in real-time.  
- Announce the detected objects through audio feedback.  
- Press **`q`** to quit the application.  

---

## 💡 Customization  

### Select Specific Object Classes  
You can customize the classes to be detected by modifying the `model.classes` variable in the script.  

**Example:**  
```python
model.classes = [0, 39]  # Detects 'person' and 'bottle'
```
### Adjust Text-to-Speech Settings

Modify the pyttsx3 parameters in the script to adjust the audio settings such as:
Volume
Speech Rate
Voice

## 🎨 Applications  
- Assisting visually impaired individuals in navigating their surroundings.  
- Providing situational awareness in unfamiliar environments.  
- Educational or experimental purposes for AI-driven accessibility tools.  

---

## 📚 Requirements  
- Python 3.8+  
- Torch  
- PyTorch Hub  
- Pyttsx3  
- OpenCV  
- NumPy  

Install all dependencies with:  
```bash
pip install torch torchvision pyttsx3 opencv-python-headless numpy
```

## 🤝 Contributing  
Contributions are welcome!  

To contribute:  
1. Fork the repository.  
2. Create a new branch and make your changes.  
3. Submit a pull request with a detailed explanation of your improvements.  







