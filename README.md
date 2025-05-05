✋ Gesture Lens – Real-Time Sign Language Alphabet Detector
-----------------------------------------------------------
Gesture Lens is a fun and simple AI tool that detects sign language alphabets in real time using your webcam! Built with love using Python, MediaPipe, and OpenCV, it helps break communication barriers and promotes inclusivity.

Whether you're learning AI or just exploring hand gestures, this project is a great starting point.

🧠 What It Does
----
    👋 Detects hand signs (A-Z) from sign language
    
    📷 Uses your webcam to see and recognize signs in real-time
    
    🧠 Trains your own custom model using your hand images
    
    🧰 Uses free tools and beginner-friendly code

🧰 Tech Used
Python

OpenCV

MediaPipe

scikit-learn

NumPy

Matplotlib

Pickle

🚀 How to Use (Step-by-Step)
Make sure Python is installed, and you're in a cool mood 😎

🔁 1. Clone this repo
bash
Copy
Edit
git clone https://github.com/yourusername/Gesture-Lens.git
cd Gesture-Lens
📦 2. Install the magic
bash
Copy
Edit
pip install opencv-python mediapipe scikit-learn matplotlib numpy
📸 3. Capture your signs
bash
Copy
Edit
python collect_imgs.py
Make different hand signs (like A, B, C...).

Images will be saved into a data/ folder.

🧷 4. Create your dataset
bash
Copy
Edit
python create_dataset.py
This creates data.pickle which holds your labeled data.

🧠 5. Train the brain
bash
Copy
Edit
python train_classifier.py
This trains your model and saves it as model.p.

👁️ 6. Run the live detector!
bash
Copy
Edit
python inference_classifier.py
Show your hand signs to your webcam and see the predictions live!

🛠️ Folder Structure
bash
Copy
Edit
Gesture-Lens/
├─ collect_imgs.py        # Capture hand sign images
├─ create_dataset.py      # Create the dataset
├─ train_classifier.py    # Train the model
├─ inference_classifier.py# Real-time sign detection
├─ data/                  # Your captured gesture images
💡 Cool Ideas
Add more letters or even full words

Make it multilingual (Sinhala or Tamil!)

Connect it with a chatbot or voice speaker

Deploy it as a simple web app using Streamlit

👦 Made by Raheesh
I'm a 17-year-old self-taught AI enthusiast from Sri Lanka 🇱🇰, passionate about using technology to solve real-world problems. Gesture Lens is one of my early AI projects — and I hope it inspires you to build your own!

🔗 LinkedIn

📧 ramzyraheesh@gmail.com

📱 WhatsApp: +94 074 220 9477

📜 License
Free to use under the MIT License. Make something awesome with it!

