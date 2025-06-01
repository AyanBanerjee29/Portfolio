---
layout: default
title: Home
---

<link rel="stylesheet" href="/assets/css/style.css">

<div class="container">
  <!-- Left: Profile Photo and Contact -->
  <div class="left-section">
    <img src="{{ site.logo }}" alt="Ayan Banerjee" style="max-width: 100%; border-radius: 12px;" />
    <h2>📫 Contact</h2>
    <ul>
      <li>📧 <a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
      <li>💼 <a href="{{ site.linkedin }}">LinkedIn</a></li>
      <li>🐙 <a href="{{ site.github }}">GitHub</a></li>
    </ul>
  </div>

  <!-- Right: Portfolio Content -->
  <div class="right-section">
    <h1>👋 Ayan Banerjee</h1>
    <p><strong>Data Scientist — Passionate in Statistics, ML & DL</strong></p>
    <p><a href="{{ site.portfolio_pdf }}">📄 Download My Portfolio (PDF)</a></p>

    <h2>ℹ️ About Me</h2>
    <p>Data Scientist with expertise in machine learning, deep learning, and statistical analysis. I love building data-driven solutions and exploring innovative algorithms.</p>

    <h2>🔥 Projects</h2>
    <h3>🎬 Movie Recommendation System with LightGCN</h3>
    <ul>
      <li>Built a GNN-based movie recommender using PyTorch Geometric</li>
      <li>Implemented BPR loss and normalized diffusion matrix on the MovieLens dataset</li>
      <li>Compared GCN, GAT, and LightGCN</li>
      <li>🔗 <a href="https://github.com/AyanBanerjee29/Movie_Recommendation_System">View on GitHub</a></li>
    </ul>
    <h3>🎵 Music Source Separation using Enhanced U-Net</h3>
    <ul>
      <li>Trained an Enhanced U-Net model on MUSDB18 to isolate vocals from audio</li>
      <li>Used spectrogram transformation and augmentation in PyTorch</li>
      <li>🔗 <a href="https://github.com/AyanBanerjee29/Music_Segmentation">View on GitHub</a></li>
    </ul>
    <h3>🧠 Bengali OCR</h3>
    <ul>
      <li>Used LeNet and ResNet models to recognize Bengali characters</li>
      <li>🔗 <a href="https://github.com/AyanBanerjee29/Bengali_Character_Recognition">View on GitHub</a></li>
    </ul>
    <h3>❤️ Heart Disease Prediction</h3>
    <ul>
      <li>Used multiple ML algorithms for binary classification</li>
      <li>🔗 <a href="https://github.com/AyanBanerjee29/Heart-Disease-Prediction-using-Machine-Learning-methods">View on GitHub</a></li>
    </ul>

    <h2>🛠 Skills</h2>
    <ul>
      <li>Languages: Python, R</li>
      <li>ML/DL: Scikit-learn, PyTorch, TensorFlow</li>
      <li>Tools: Jupyter Notebook, VS Code</li>
      <li>Data Tools: Pandas, NumPy, Matplotlib</li>
    </ul>

    <h2>🎓 Education</h2>
    <ul>
      <li>M.Sc. in Big Data Analytics | RKMVERI | 2023–2025</li>
      <li>B.Sc. in Mathematics | Serampore College, Calcutta University | 2020–2023</li>
    </ul>
  </div>
</div>
