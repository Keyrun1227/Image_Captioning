# ✨ Image Captioning Project 🎈

Welcome to the Image Captioning project! Unleash the power of AI to generate captivating captions for your images.

## 🚀 Overview
Harness the capabilities of Vision Transformer (ViT) and GPT-2 for creating an Image Captioning web application. This Flask-based project allows users to upload images and receive multiple AI-generated captions.

## 🧠 Models Used
- **Vision Transformer (ViT):** Processes images and extracts features.
- **GPT-2 (Generative Pre-trained Transformer 2):** Generates creative and contextually relevant captions.

## ✨ Features
- Upload images to receive captivating captions.
- Dynamically generate multiple captions for a single image.
- Real-time visualization of uploaded image and generated captions.

## 🛠 Dependencies
- Flask: A micro web framework for Python.
- Transformers Library: Utilized for integrating ViT and GPT-2 models.
- PIL (Pillow): Python Imaging Library for image processing.
- Matplotlib: Plotting library for creating result images.

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Flask application with `python app.py`.
4. Open your browser and go to `http://localhost:5000`.

## 🌐 Web Interface
- **Home Page (`index.html`):** Allows users to upload images and set the number of captions to generate.
- **Result Page (`result.html`):** Displays the uploaded image along with multiple AI-generated captions.

## 🌈 Project Structure
- `app.py`: Flask application handling image upload and caption generation.
- `templates`: Folder containing HTML templates for web pages.
- `static`: Folder for storing static files like images.

## 🌍 External Services
- **nlpconnect/vit-gpt2-image-captioning Model:** Pre-trained model for ViT and GPT-2.

## 👩‍💻 Usage
1. Upload an image on the home page.
2. Set the desired number of captions to generate.
3. Click "Upload" and behold the magic of AI-generated captions!

## 🤝 Contributing
Contributions are welcome! Feel free to open issues and pull requests.

Happy Developing🎉
