# Somnipathylab
Struktur Direktori 
somnipathy-lab/
├── docs/                          # Root untuk GitHub Pages (Frontend + Client AI)
│   ├── index.html                 # Halaman utama & pengantar
│   ├── skrining.html              # Form kuesioner tidur (FR-01)
│   ├── hasil.html                 # Tampilan hasil, faktor, & rekomendasi (FR-05, FR-06)
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── somnipathy_agent.js    # Inti Agen Cerdas (Algoritma Bab 5.5)
│   │   ├── knowledge_base.js      # Aturan rekomendasi & edukasi tidur
│   │   └── main.js                # Pengendali UI & localStorage riwayat (FR-09)
│   └── model/
│       └── decision_tree.json     # Hasil ekspor model Python untuk browser
├── machine_learning/              # Pipeline pelatihan & evaluasi (Bab 5.4 & 6.4)
│   ├── train_model.py             # Training, evaluasi, & ekspor joblib + JSON
│   ├── data/
│   │   ├── raw/                   # Dataset Kaggle (Sleep Health and Lifestyle)
│   │   └── processed/             # Dataset bersih
│   └── models/
│       └── decision_tree.joblib   # Model standar sesuai Lampiran B
├── tests/                         # Pengujian unit (Bab 6.4)
├── requirements.txt
└── README.md
