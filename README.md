# 🎧 Content-Based Music Recommendation System

A content-based music recommendation engine that suggests similar songs based on audio features extracted from raw `.wav` files. This system avoids relying on user preferences or collaborative filtering, instead using mathematical analysis of audio signals to find sonic similarity between tracks.

---

## 🚀 Features

- Extracts audio features using `librosa`
- Calculates similarity between tracks using cosine distance
- Supports multiple genres and audio formats
- Visualizes feature space with PCA and t-SNE
- Modular pipeline for feature extraction, normalization, and recommendation

---

## 🧠 Tech Stack

- Python 3.x
- `librosa` – Audio feature extraction
- `NumPy`, `pandas` – Data manipulation
- `scikit-learn` – Model building and PCA
- `Matplotlib`, `seaborn` – Visualizations

---

## 📂 Project Structure

```
music-recommender/
├── music_recommender.ipynb        # Main notebook
├── utils/
│   └── feature_extraction.py      # Custom feature extractor (optional)
├── dataset/
│   └── [genre folders]/.wav       # Raw audio files
├── requirements.txt               # Dependencies
└── README.md                      # Project documentation
```

---

## 📊 Features Extracted

- **Chroma Frequencies**
- **Spectral Centroid**
- **Spectral Rolloff**
- **Zero Crossing Rate**
- **MFCCs (Mel-Frequency Cepstral Coefficients)**
- **Tempo/BPM**

---

## 🔍 How It Works

1. Extracts features from raw audio using `librosa`
2. Normalizes and stores feature vectors
3. Calculates cosine similarity between tracks
4. Recommends top-N similar tracks to the input

---

## 💻 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/music-recommender.git
cd music-recommender
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the notebook**

Open `music_recommender.ipynb` and follow the steps inside.

---

## 📈 Sample Output

![Recommendation Matrix](https://fakeimg.pl/350x200/?text=Similarity+Matrix&font=lobster)  
*Above: Cosine similarity matrix of selected tracks.*

---

## 🧠 Future Improvements

- Add genre-based filtering
- Improve feature ranking using supervised models
- Integrate with Spotify API for real-time suggestions
- Build a Streamlit web UI

---

## 📬 Contact

For queries, feedback, or collaboration, reach out at:  
📧 **bhavye.23fe10cds00128@muj.manipal.edu**

---

## 🪪 License

This project is open-sourced under the [MIT License](LICENSE).

---

⭐️ If you find this useful, consider giving the repo a star!
