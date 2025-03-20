# Praktikum Algoritma Pencarian (Informed Search)
**2306141_Rabiul Tsani Ghifarulhaq A**

## 📌 Deskripsi
Repository ini berisi implementasi berbagai algoritma pencarian berbasis informasi (*Informed Search*) menggunakan **Python**. Algoritma yang tersedia meliputi:

- **Greedy Best-First Search (GBFS)**: Memilih node berdasarkan estimasi heuristik ke tujuan tanpa mempertimbangkan biaya perjalanan sebelumnya.
- **A* Tree Search**: Algoritma A* dengan pendekatan *tree search*, tanpa menyimpan daftar node yang telah dieksplorasi.
- **A* Graph Search**: Algoritma A* dengan pendekatan *graph search*, yang menyimpan daftar node yang telah dikunjungi untuk menghindari eksplorasi ulang.

Algoritma-algoritma ini digunakan untuk mencari jalur optimal dalam suatu graph dengan memanfaatkan informasi heuristik untuk meningkatkan efisiensi pencarian.

## 📂 Struktur Repository
- `greedy_best_first.py` → Implementasi *Greedy Best-First Search*
- `a_star_tree.py` → Implementasi *A* dengan pendekatan *Tree Search*
- `a_star_graph.py` → Implementasi *A* dengan pendekatan *Graph Search*

Setiap file dilengkapi dengan contoh penggunaan yang dapat langsung dijalankan.

## 🚀 Cara Menjalankan
1. **Clone repository ini ke komputer lokal atau Google Colab**:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
2. **Jalankan file Python yang diinginkan**:
   ```bash
   python greedy_best_first.py
   python a_star_tree.py
   python a_star_graph.py
   ```


