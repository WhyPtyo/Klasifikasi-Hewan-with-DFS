Bahasa Indonesia
Klasifikasi Hewan di Kebun Binatang dengan Struktur Pohon Taksonomi
Proyek ini merupakan bagian dari Ujian Akhir Semester yang berfokus pada implementasi dan eksplorasi struktur data pohon (tree) untuk mengklasifikasikan dan mencari hewan berdasarkan taksonomi mereka. Dengan memanfaatkan data karakteristik hewan dari kebun binatang dan struktur taksonomi JSON, proyek ini menunjukkan bagaimana algoritma pencarian Depth-First Search (DFS) dapat diaplikasikan untuk navigasi dan penemuan informasi dalam hierarki kompleks.

Fitur Utama
Pembangunan Pohon Taksonomi: Membangun representasi pohon dari struktur taksonomi hewan berdasarkan berkas taxonomy_structure.json.

Analisis Dataset Hewan: Menggunakan zoo_dataset.csv untuk memahami karakteristik berbagai hewan.

Pencarian DFS: Mengimplementasikan algoritma Depth-First Search (DFS) untuk mencari hewan atau kategori taksonomi dalam struktur pohon.

Visualisasi Data: Menyajikan data dan hasil analisis melalui berbagai visualisasi yang informatif.

Struktur Proyek
.
├── Klasifikasi_Hewan_Zoo.ipynb
├── zoo_dataset.csv
├── taxonomy_structure.json
└── README.md

Klasifikasi_Hewan_Zoo.ipynb: Berkas Jupyter Notebook utama yang berisi seluruh kode, analisis, dan implementasi proyek.

zoo_dataset.csv: Berkas dataset yang mengandung informasi karakteristik hewan.

taxonomy_structure.json: Berkas JSON yang mendefinisikan struktur hierarki taksonomi hewan.

README.md: Berkas penjelasan proyek ini.

Dependensi
Untuk menjalankan proyek ini, Anda perlu menginstal pustaka Python berikut:

pandas

numpy

matplotlib

seaborn

json (biasanya sudah tersedia di Python standar)

Anda dapat menginstalnya menggunakan pip:

pip install pandas numpy matplotlib seaborn

Cara Menjalankan Proyek
Ikuti langkah-langkah di bawah ini untuk menjalankan dan menjelajahi proyek:

Kloning Repositori:

git clone https://github.com/WhyPtyo/Project-SDA-Klasifikasi-Hewan.git
cd Project-SDA-Klasifikasi-Hewan

Pastikan Berkas Ada: Pastikan berkas zoo_dataset.csv dan taxonomy_structure.json berada di direktori yang sama dengan Klasifikasi_Hewan_Zoo.ipynb.

Buka Jupyter Notebook:

jupyter notebook Klasifikasi_Hewan_Zoo.ipynb

Jalankan Sel Secara Berurutan: Ikuti petunjuk di dalam notebook dan jalankan setiap sel secara berurutan dari atas ke bawah untuk melihat alur kerja, analisis, pembangunan pohon, implementasi DFS, dan visualisasi hasilnya.

Hasil dan Analisis
Notebook ini akan memandu Anda melalui tahapan:

Pemuatan dan eksplorasi data.

Konstruksi pohon taksonomi dari data JSON.

Implementasi fungsi pencarian DFS untuk menemukan spesies atau kategori taksonomi tertentu.

Visualisasi hubungan antar hewan dan karakteristiknya, serta hasil pencarian.

Proyek ini diharapkan memberikan pemahaman yang jelas tentang bagaimana struktur data pohon dan algoritma pencarian dapat digunakan untuk mengatur dan mengekstraksi informasi dari data hierarkis.

English
Zoo Animal Classification with Taxonomic Tree Structure
This project is part of a Final Semester Examination, focusing on the implementation and exploration of tree data structures for classifying and searching animals based on their taxonomy. By leveraging animal characteristic data from a zoo dataset and a JSON taxonomic structure, this project demonstrates how Depth-First Search (DFS) algorithms can be applied to navigate and discover information within complex hierarchies.

Key Features
Taxonomic Tree Construction: Building a tree representation of animal taxonomic structures from the taxonomy_structure.json file.

Animal Dataset Analysis: Utilizing zoo_dataset.csv to understand the characteristics of various animals.

DFS Search: Implementing the Depth-First Search (DFS) algorithm to find animals or taxonomic categories within the tree structure.

Data Visualization: Presenting data and analysis results through informative visualizations.

Project Structure
.
├── Klasifikasi_Hewan_Zoo.ipynb
├── zoo_dataset.csv
├── taxonomy_structure.json
└── README.md

Klasifikasi_Hewan_Zoo.ipynb: The main Jupyter Notebook file containing all the project code, analysis, and implementation.

zoo_dataset.csv: The dataset file containing animal characteristic information.

taxonomy_structure.json: The JSON file defining the hierarchical taxonomic structure of animals.

README.md: This project explanation file.

Dependencies
To run this project, you need to install the following Python libraries:

pandas

numpy

matplotlib

seaborn

json (usually available in standard Python)

You can install them using pip:

pip install pandas numpy matplotlib seaborn

How to Run the Project
Follow the steps below to run and explore the project:

Clone the Repository:

git clone https://github.com/WhyPtyo/Project-SDA-Klasifikasi-Hewan.git
cd Project-SDA-Klasifikasi-Hewan

Ensure Files are Present: Make sure zoo_dataset.csv and taxonomy_structure.json are in the same directory as Klasifikasi_Hewan_Zoo.ipynb.

Open Jupyter Notebook:

jupyter notebook Klasifikasi_Hewan_Zoo.ipynb

Run Cells Sequentially: Follow the instructions within the notebook and execute each cell sequentially from top to bottom to see the workflow, analysis, tree construction, DFS implementation, and visualization of results.

Results and Analysis
This notebook will guide you through the stages of:

Data loading and exploration.

Construction of the taxonomic tree from JSON data.

Implementation of DFS search functions to find specific species or taxonomic categories.

Visualization of animal relationships and characteristics, as well as search results.

This project is expected to provide a clear understanding of how tree data structures and search algorithms can be utilized to organize and extract information from hierarchical data.
