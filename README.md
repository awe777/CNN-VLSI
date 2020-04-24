# CNN-VLSI
Referensi CNN untuk Kelas VLSI EL4138, banyak berhubungan dengan https://github.com/awe777/keras-yolo3 untuk pembuatan file anotasi, konversi .weights menjadi file .h5, dan lain-lain.

# Index
1. CNN_MNIST berisi model CNN refrensi
2. model_processing_quantized berisi refrensi cara kuantisasi, verifikasi kuantisasi, dan cara mengambil weight terkuantisasi

# Dependencies
1. Python 3.5-3.7
2. Numpy
3. Keras
4. Matplotlib
5. Tensorflow (2.0+)
6. Jupyter notebook

# Cara menjalankan notebook di linux/mac 
Jika anda pakai windows, bisa memakai install.bat yang terdapat di root proyek ini

1. Direkomendasikan anda mendownload paket software conda https://docs.anaconda.com/anaconda/install/
2. Buat virtual environment conda https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands
3. Activate environment conda (source activate myenv) https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment
4. Install dependencies di environment tersebut (dengan pip install ...)
5. Install nb_kernels (conda install nb_conda)
6. Download dan jalankan notebook (jupyter notebook)

# Note
Sebelum inference menggunakan generated weight file, harap file \*.h5 yang sudah dibuat divalidasi dengan menjalankan cnn_tinyYolov3.ipynb tanpa melakukan training (men-*toggle comment* pada setiap training model).

(Kode asal) Dibuat Oleh:

M. Rifqi Daffa S EL14 (pemilik repo awal: https://github.com/rDaffa/CNN-VLSI)

Sayyid Irshadul Ibad EL15

Di-_fork_ Oleh:

Joshua Adiel Wijaya Tekkom 2017 (SPS)
