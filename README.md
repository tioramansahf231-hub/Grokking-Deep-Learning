# Grokking Deep Learning - Code Reproduction & Theory Summary

Repository ini berisi reproduksi kode dan penjelasan teoretis dari buku **Grokking Deep Learning** karya Andrew W. Trask (Manning Publications) untuk pemenuhan tugas mata kuliah Deep Learning.

---

## Ringkasan Bab (Chapter Summary)

### Chapter 3: Introduction to Neural Prediction (Forward Propagation)
- **Konsep Kunci:** Forward propagation, bobot (weights), perkalian titik (*dot product*), dan jaringan berlapis (*stacked neural network*).
- **Inti Materi:** Mempelajari bagaimana neural network melakukan prediksi dengan mengalikan data input dan bobot. Mengoperasikan 4 arsitektur: single input-output, multiple inputs, multiple outputs, hingga jaringan multi-layer.

### Chapter 4: Introduction to Neural Learning (Gradient Descent)
- **Konsep Kunci:** Predict, Compare, Learn; Mean Squared Error (MSE), Gradient Descent, dan Learning Rate ($\alpha$).
- **Inti Materi:** Mengukur tingkat kesalahan (*error*) model dan memperbarui nilai bobot secara sistematis menggunakan turunan (*derivative*) agar error mendekati nol.

### Chapter 5: Learning Multiple Weights at a Time (Generalizing Gradient Descent)
- **Konsep Kunci:** Stochastic Gradient Descent pada banyak input & output, serta penyesuaian matriks bobot.
- **Inti Materi:** Memperluas metode gradient descent untuk memperbarui banyak bobot sekaligus secara simultan.

### Chapter 6: Building Your First Deep Neural Network (Backpropagation)
- **Konsep Kunci:** Non-linearity (ReLU), Backpropagation, dan Hidden Layers.
- **Inti Materi:** Menggunakan fungsi aktivasi untuk mempelajari hubungan non-linear dan mendistribusikan error dari output layer kembali ke hidden layer.

---

## Struktur Repository
- `Chapter_03.ipynb`
- `README.md`
