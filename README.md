DeepFakeGuard 🎙️🛡️

CMPE 491 Senior Design Project – TED University

DeepFakeGuard is a real-time speech analysis system that detects whether an audio is AI-generated or human. The system uses machine learning techniques to extract and analyze speech features like MFCC, pitch, and shimmer.

🚀 Project Goals

Detect AI-generated (deepfake) speech

Provide real-time analysis

Ensure high accuracy and low false positives

Design a user-friendly and interpretable interface

📁 Folder Structure

DeepFakeGuard/
├── data/            # Audio samples (not shared publicly)
├── models/          # Trained models
├── notebooks/       # Jupyter notebooks for experiments
├── src/             # Main source code
├── ui/              # User interface (e.g., Streamlit)
├── docs/            # Reports & documents
├── tests/           # Unit tests
├── README.md        # This file
├── requirements.txt # Dependencies
└── .gitignore       # Files to ignore in Git

⚙️ How to Run

Install dependencies:

pip install -r requirements.txt

Run detection:

python src/main.py --input path_to_audio.wav

Or run the interface (optional):

streamlit run ui/app.py

👥 Team

Arda Ali Altıncı

Yüşa Emir Metin

Mustafa Vanlıoğlu

Mert Koçoğlu

📘 Reports

🔗 References

Firc, Anton, et al. “Deepfake Speech Detection: A Spectrogram Analysis.” ACM/SIGAPP Symposium on Applied Computing, 2024.

IEEE. “Synthetic Speech Detection Using Deep Neural Networks.” ICASSP, 2024.

IEEE. “Reliability Estimation for Synthetic Speech Detection.” ICASSP, 2023.

IEEE. “Deepfake Generation and Detection - An Exploratory Study.” ICME, 2023.

IEEE. “Application of Machine Learning Techniques for Generated Speech Detection.” IEEE Big Data, 2024.

NPR. “Send in the Clones: Using Artificial Intelligence to Digitally Replicate Human Voices.” 2022.

Bird, Jordan J., and Ahmad Lotfi. “Real-time Detection of AI-Generated Speech for DeepFake Voice Conversion.” arXiv, 2023.



📄 License

MIT License
