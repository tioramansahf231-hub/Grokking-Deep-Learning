# Grokking Deep Learning - Code Reproduction & Theory Summary

Repository ini berisi reproduksi kode dan penjelasan teoretis dari buku **Grokking Deep Learning** karya Andrew W. Trask (Manning Publications).

---

## Ringkasan Bab (Chapter Summary)

### Chapter 1: Introducing Deep Learning
- **Konsep Kunci:** Pengenalan deep learning, kegunaan, dan prasyarat dasar (Python, NumPy, Jupyter Notebook).
- **Inti Materi:** Deep learning adalah bagian dari machine learning yang berfokus pada pelatihan jaringan saraf tiruan (neural networks) tanpa memerlukan matematika tingkat tinggi di awal.

### Chapter 2: Fundamental Concepts (How Do Machines Learn?)
- **Konsep Kunci:** Supervised vs Unsupervised Learning, Parametric vs Nonparametric Learning.
- **Inti Materi:** Supervised learning mengubah set data input ke output berdasar pasangan target. Model parametrik menggunakan bobot yang disesuaikan secara berulang.

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

### Chapter 7: How to Picture Neural Networks (Conceptualizing Abstract Frameworks)
- **Konsep Kunci:** Visualisasi matriks & vektor, arsitektur jaringan, dan abstraksi ruang fitur.
- **Inti Materi:** Menyederhanakan cara berpikir tentang jaringan saraf dari sekadar titik/garis menjadi operasi matriks-vektor berdimensi tinggi.

### Chapter 8: Learning Signal and Ignoring Noise (Regularization & Batching)
- **Konsep Kunci:** Overfitting, Generalization, Dropout, dan Mini-batch SGD pada dataset MNIST.
- **Inti Materi:** Mencegah model menghafal *noise* pada data latih menggunakan Dropout dan mengoptimalkan proses pelatihan menggunakan mini-batch.

### Chapter 9: Modeling Probabilities and Nonlinearities (Activation Functions)
- **Konsep Kunci:** Softmax, Sigmoid, Tanh, dan turunan fungsi aktivasi.
- **Inti Materi:** Memilih dan menerapkan fungsi aktivasi yang sesuai pada output layer untuk memodelkan probabilitas klasifikasi multi-kelas secara akurat.

### Chapter 10: Neural Networks That Understand Pictures (CNNs)
- **Konsep Kunci:** Convolutional Neural Networks (CNN), Reusing weights, Feature maps, dan Kernel/Filter.
- **Inti Materi:** Menggunakan operasi konvolusi lokal untuk mendeteksi fitur spasial (seperti tepi dan bentuk) pada data gambar secara efisien.

### Chapter 11: Neural Networks That Understand Language (Word Embeddings)
- **Konsep Kunci:** Word Embeddings, Word2Vec, Vektor Semantik, dan Analogi Kata.
- **Inti Materi:** Memetakan kata-kata ke dalam ruang vektor kontinu sehingga makna semantik dan hubungan antar-kata dapat dihitung secara matematis.

### Chapter 12: Neural Networks That Write Like Shakespeare (Recurrent Layers)
- **Konsep Kunci:** Recurrent Neural Networks (RNN), Hidden state, dan Unrolling over time.
- **Inti Materi:** Mengolah data sekuensial berpanjang variabel dengan menyimpan memori (*hidden state*) dari langkah sebelumnya.

### Chapter 13: Introducing Automatic Optimization (Building a Framework)
- **Konsep Kunci:** Automatic Differentiation (Autograd), Computation Graph, dan Tensor.
- **Inti Materi:** Membangun *deep learning framework* sederhana dari nol untuk mengotomatiskan proses kalkulasi gradien dan backpropagation.

### Chapter 14: Learning with Curriculum (Optimization & Speed)
- **Konsep Kunci:** Curriculum Learning, Learning rate decay, dan Strategi pelatihan.
- **Inti Materi:** Meningkatkan kecepatan dan stabilitas konvergensi model dengan mengatur urutan serta kompleksitas data latih yang diberikan.

### Chapter 15: Movement Towards Deep Reinforcement Learning
- **Konsep Kunci:** Reinforcement Learning, Agent, Environment, Reward, dan Policy.
- **Inti Materi:** Menggabungkan deep learning dengan reinforcement learning agar agen dapat mengambil keputusan optimal melalui interaksi langsung dengan lingkungan.

---

## Struktur Repository
- `Chapter_03.ipynb`
- `Chapter_04.ipynb`
- `Chapter_05.ipynb`
- `Chapter_06.ipynb`
- `Chapter_07.ipynb`
- `Chapter_08.ipynb`
- `Chapter_09.ipynb`
- `Chapter_10.ipynb`
- `Chapter_11.ipynb`
- `Chapter_12.ipynb`
- `Chapter_13.ipynb`
- `Chapter_14.ipynb`
- `Chapter_15.ipynb`
- `README.md`
