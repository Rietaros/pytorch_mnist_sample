# pytorch_mnist_sample
pytorch-mnist.ipnyb is jupyter notebook for running sample code to train and eval MNIST Digit Recognition Task

# PyTorch MNIST - Parameter Tuning ⚙️

Repositori ini adalah fork dari repositori publik [`https://github.com/Rietaros/pytorch_mnist_sample`](https://github.com/Rietaros/pytorch_mnist_sample)  dan berisi eksperimen tuning hyperparameter untuk meningkatkan akurasi model CNN pada dataset MNIST.

## Tujuan 🎯

Tujuan dari proyek ini adalah untuk mencapai akurasi > 90% pada dataset MNIST dengan memodifikasi hyperparameter `learning_rate` dan `momentum` pada model CNN yang ada di notebook `pytorch-mnist.ipynb`.

## Langkah-langkah yang Dilakukan 🛠️

1. **Fork dan Clone:** Repositori asli di-fork dan di-clone ke lokal.
2. **Menjalankan Notebook:** Notebook `pytorch-mnist.ipynb` dijalankan di Google Colab untuk mendapatkan akurasi baseline.  Akurasi baseline: (Isi dengan akurasi baseline yang didapat).
3. **Membuat Branch Baru:** Branch baru dengan nama `parameter-testing` dibuat: `git checkout -b parameter-testing`.
4. **Modifikasi Hyperparameter:** Hyperparameter `learning_rate` dan `momentum` dimodifikasi di notebook `pytorch-mnist.ipynb`.
    * **Nilai Awal:** (Sebutkan nilai awal `learning_rate` dan `momentum`)
    * **Nilai Modifikasi:** (Sebutkan nilai akhir `learning_rate` dan `momentum` setelah tuning)
    * **Alasan Perubahan:** (Jelaskan alasan di balik perubahan nilai hyperparameter, misalnya berdasarkan hasil eksperimen, referensi, dsb.)
5. **Commit dan Push:** Perubahan di-commit dan di-push ke branch `parameter-testing` di repositori fork.
6. **Pull Request:** Pull Request dibuat dari branch `parameter-testing` ke repositori asli: [`https://github.com/Rietaros/pytorch_mnist_sample`](https://github.com/Rietaros/pytorch_mnist_sample).  [Link ke Pull Request](https://github.com/Rietaros/pytorch_mnist_sample/pull/34)


## Hasil 🚀

Setelah melakukan tuning hyperparameter, akurasi yang dicapai adalah: (Isi dengan akurasi akhir setelah tuning).

## Link Repositori Fork 🔗

[Link ke Repositori Fork Anda](https://github.com/Marsyanda04/pytorch_mnist_sample)

## Kesimpulan 🤔

Hyperparameter yang dituning yaitu learning rate sebesar 0.01 dan momentum sebesar 0.9 yang menghasilkan akurasi sebesar 96.60%.


## Cara Menjalankan Notebook 💻

1. Buka notebook `pytorch-mnist.ipynb` di Google Colab.
2. Pastikan runtime di set ke GPU untuk mempercepat proses training.
3. Jalankan semua cell di notebook.


## Dependencies 📦

* PyTorch
* Torchvision
* Matplotlib


Semoga informasi ini bermanfaat! 🎉

## Reference
https://github.com/jiuntian/pytorch-mnist-example
