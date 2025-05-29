# Gender and Age Detection 🔍

This project uses computer vision and deep learning to detect the **gender** and **age** of individuals from images or video streams in real-time. Built using Python and OpenCV, it leverages pre-trained models to perform accurate predictions.

## 🔗 Project Repository
GitHub: [Sparshmogveer/gender-and-Age-Detection-master](https://github.com/Sparshmogveer/gender-and-Age-Detection-master)

---

## 🚀 Features

- Real-time webcam input and image detection
- Predicts age range and gender
- Uses pre-trained deep learning models
- Easy-to-use and well-documented code

---

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Deep Learning Models (Caffe-based)

---

## 📁 Project Structure

gender-and-Age-Detection-master/
│
├── age_deploy.prototxt # Age model configuration
├── age_net.caffemodel # Age detection model
├── gender_deploy.prototxt # Gender model configuration
├── gender_net.caffemodel # Gender detection model
├── detect.py # Main script to run detection
├── sample.jpg # Sample test image
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sparshmogveer/gender-and-Age-Detection-master
   cd gender-and-Age-Detection-master
Install dependencies:

bash
Copy
Edit
pip install opencv-python numpy
Run the detection script:

For image input:

bash
Copy
Edit
python detect.py --image sample.jpg
For real-time webcam input:

bash
Copy
Edit
python detect.py
🎯 Output Example
The script will display the input with bounding boxes showing predicted gender and age range.

yaml
Copy
Edit
Example Output:
Gender: Male | Age: 25-32 
![M](https://github.com/user-attachments/assets/88476cae-ee9e-4af2-beba-f1b1f406fa3a)
![F](https://github.com/user-attachments/assets/e974d29f-ebc5-4fc9-a22a-1184bf8e7f24)


📌 Pre-trained Models Used

Age prediction model trained on Adience dataset

Gender prediction model trained on IMDB-WIKI dataset

Caffe-based .caffemodel and .prototxt architecture

📜 License
This project is for educational and research purposes only.

🤝 Contributing
Feel free to fork the repo and submit pull requests for improvements or bug fixes!

👨‍💻 Author
Sparsh Mogveer

GitHub: @Sparshmogveer

LinkedIn:  [https://www.linkedin.com/in/sparsha-b-t-3157592a2/]
