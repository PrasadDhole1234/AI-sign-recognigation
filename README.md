# Hand Gesture Data Collection

This project captures hand gesture images using **OpenCV** and **cvzone’s HandTrackingModule**. The script detects a hand from a webcam feed, crops it, normalizes the size to a white canvas, and saves it as a dataset for further use (e.g., training gesture recognition models).

---------------------------

## ✨ Features
- Real-time hand detection using **cvzone**.  
- Crops and centers hand images onto a fixed **300x300 white canvas**.  
- Automatically adjusts image scaling based on hand aspect ratio.  
- Saves captured images with unique filenames.  
- Useful for building **gesture recognition datasets**.  

---

## 📂 Project Structure
Hand-Gesture-Data-Collection/
│── Data/ # Folder where images will be saved (e.g., Data/Z)
│── collect.py # Main script (your code)
│── README.md # Documentation


---------------------------------------------------------------------------------

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/Hand-Gesture-Data-Collection.git
cd Hand-Gesture-Data-Collection

pip install opencv-python cvzone numpy

mkdir -p Data/Z

python collect.py
```
Webcam will open and start detecting your hand.

Press s to save the current processed hand image to Data/Z.

Images are saved as:Image_<timestamp>.jpg

📦 Dependencies
```Python 3.x
opencv-python
cvzone
numpy
