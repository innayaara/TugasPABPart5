# Laporan Pengujian Shopping Cart Flutter

---

<details>
<summary><b>1. Pengujian Add Product 3x</b></summary>

Pengujian dilakukan dengan menambahkan satu produk sebanyak tiga kali dengan menekan tombol **Add** secara berulang.  
Setelah itu membuka halaman Cart untuk melihat hasilnya.

### Hasil yang diperoleh:
- Quantity otomatis menjadi 3
- Total harga berubah sesuai jumlah item

Berikut tampilan hasil pengujian:

<img width="839" height="730" alt="Screenshot 2026-02-23 230231" src="https://github.com/user-attachments/assets/ba56cbf3-16c3-40ef-b3ad-6089c6e2bde5" />

</details>

---

<details>
<summary><b>2. Pengujian Add Beberapa Produk Berbeda</b></summary>

Pengujian dilakukan dengan menambahkan beberapa produk berbeda dari halaman Product List tanpa membuka halaman Cart terlebih dahulu.

### Hasil yang diperoleh:
- Badge pada icon cart menampilkan jumlah total item secara **real-time**
- Angka pada badge sesuai dengan jumlah produk yang ditambahkan

Berikut tampilan hasil pengujian:

<img width="848" height="850" alt="image" src="https://github.com/user-attachments/assets/e4a0ac7f-cb29-4c1d-8464-d99bd9c1b8d0" />

<img width="847" height="854" alt="image" src="https://github.com/user-attachments/assets/cdc0a0db-45f2-4450-b079-1847a59ec3d6" />

<!-- Screenshot di sini -->

</details>

---

<details>
<summary><b>3. Pengujian Increase Quantity</b></summary>

Pengujian dilakukan dengan menekan tombol tambah **( + )** pada salah satu produk di halaman Cart.

### Hasil yang diperoleh:
- Quantity bertambah sesuai jumlah klik
- Total harga langsung terupdate otomatis
- Tidak perlu refresh halaman

Berikut tampilan hasil pengujian:

<!-- Screenshot di sini -->

</details>

---

<details>
<summary><b>4. Pengujian Decrease Quantity sampai 1</b></summary>

Pengujian dilakukan dengan menekan tombol kurang **( - )** hingga quantity tersisa 1.

### Hasil yang diperoleh:
- Produk tetap berada di dalam cart
- Sistem tidak langsung menghapus item

Berikut tampilan hasil pengujian:

<!-- Screenshot di sini -->

</details>

---

<details>
<summary><b>5. Pengujian Decrease Quantity sampai 0</b></summary>

Pengujian dilakukan dengan menekan tombol kurang **( - )** kembali hingga quantity menjadi 0.

### Hasil yang diperoleh:
- Produk otomatis terhapus dari cart
- Tampilan cart langsung terupdate

Berikut tampilan hasil pengujian:

<!-- Screenshot di sini -->

</details>

---

<details>
<summary><b>6. Pengujian Clear Cart</b></summary>

Pengujian dilakukan dengan menekan tombol **Clear Cart** untuk menghapus seluruh item sekaligus.

### Hasil yang diperoleh:
- Semua produk berhasil dihapus
- Muncul pesan bahwa cart kosong

Berikut tampilan hasil pengujian:

<!-- Screenshot di sini -->

</details>

---

<details>
<summary><b>7. Pengujian Navigasi Kembali ke Halaman Produk</b></summary>

Pengujian dilakukan dengan kembali ke halaman **Product List** setelah melakukan perubahan pada cart.

### Hasil yang diperoleh:
- Badge tetap menampilkan jumlah item yang sesuai
- Data cart tetap tersimpan dengan baik meskipun berpindah halaman

Berikut tampilan hasil pengujian:

<!-- Screenshot di sini -->

</details>
