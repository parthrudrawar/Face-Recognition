# Face-Recognition
Face Recognition System using OpenCV, FaceNet, and Deep Learning
🔍 Overview
This project is a real-time face recognition system designed to identify and verify individuals using deep learning-based face embeddings. Leveraging OpenCV, FaceNet, and advanced deep learning techniques, the system can detect and recognize faces from images and live webcam feeds.
Originally designed for office security and attendance tracking, the system enables automatic recognition of registered employees and flags unregistered or unknown individuals, enhancing both efficiency and safety.

🚀 Features:
🔴 Real-time face detection and recognition via webcam
🧠 High-accuracy deep learning-based face embedding (FaceNet)
📷 Image and video stream input support
🧾 Employee registration and face encoding database
🔐 Security-focused: Flags unrecognized individuals
⚡ Optimized for speed and performance

🛠️ Technologies Used:
1.Python
2.OpenCV – Real-time computer vision
3.FaceNet – Face embedding for recognition
4.NumPy, TensorFlow/Keras – Deep learning and data handling
5.Face Embedding & Cosine Similarity – Face verification

💡 Use Cases:
🔒 Office security systems
🕒 Automated attendance tracking
👮‍♂️ Access control systems
🏫 Smart classrooms or corporate meetings

🧑‍💻 How It Works:
Face Detection – Detect faces from webcam/video/image using OpenCV.
Embedding Generation – Use FaceNet to convert detected faces into 128D face embeddings.
Comparison – Compare face embeddings with the database using cosine similarity.
Recognition – Identify known individuals or flag unknowns

 Installation:
 # Clone the repository
git clone https://github.com/yourusername/face-recognition-system.git
cd face-recognition-system

# Install dependencies
pip install -r requirements.txt

Usage:
# Run the main script
python main.py

📬 Contact
For any queries or contributions, feel free to reach out at rudrawarparth99@gmail.com.


