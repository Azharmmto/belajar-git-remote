# Belajar Git Remote

Selamat datang di repositori untuk belajar dan berlatih tentang `git remote`!

Repositori ini dibuat sebagai "bak pasir" (sandbox) untuk mempraktikkan berbagai perintah yang berkaitan dengan pengelolaan repositori jarak jauh (remote) di Git.

## 🎯 Tujuan Repositori Ini

*   Memahami konsep repositori remote di Git.
*   Mempraktikkan cara menambah, mengubah nama, dan menghapus remote.
*   Belajar cara melakukan sinkronisasi (push & pull) dengan repositori remote yang berbeda.
*   Menjadi tempat yang aman untuk mencoba perintah `git remote` tanpa takut merusak proyek penting.

## 📚 Perintah Utama yang Akan Dipelajari

Berikut adalah beberapa perintah `git remote` yang bisa Anda praktikkan di sini:

1.  **Melihat daftar remote:**
    ```bash
    git remote -v
    ```

2.  **Menambah remote baru:**
    ```bash
    git remote add <nama-remote> <url-repositori>
    ```
    Contoh: `git remote add backup https://github.com/user/repo-backup.git`

3.  **Mengubah nama remote:**
    ```bash
    git remote rename <nama-lama> <nama-baru>
    ```
    Contoh: `git remote rename origin upstream`

4.  **Menghapus remote:**
    ```bash
    git remote remove <nama-remote>
    ```
    Contoh: `git remote remove backup`

5.  **Mengubah URL sebuah remote:**
    ```bash
    git remote set-url <nama-remote> <url-baru>
    ```

## 🚀 Cara Memulai

1.  **Clone repositori ini** dan masuk ke dalam direktorinya.
2.  **Lihat remote yang sudah ada** dengan `git remote -v`. Secara default, Anda akan melihat remote `origin`.
3.  **Praktikkan perintah-perintah di atas!** Coba tambahkan remote baru, ubah namanya, lalu hapus. Selamat mencoba!
