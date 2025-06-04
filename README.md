# 🧪 Pengujian Mini Habit Tracker

Berikut adalah dokumentasi pengujian dari fitur-fitur utama pada aplikasi Mini Habit Tracker, dilengkapi dengan tangkapan layar pada setiap langkah.

---

### ✅ 1. Jalankan Aplikasi
Aplikasi berhasil dijalankan menggunakan `flutter run`.

![Jalankan Aplikasi](screenshots/flutter_run.png)

---

### ✍️ 2. Uji Strikethrough
Centang dan batalkan centang pada habit. Teks akan dicoret ketika habit ditandai selesai.

![Strikethrough](screenshots/strikethrough.png)

---

### ➕ 3. Uji Tambah Habit

**a. Klik tombol + di AppBar.**

![Tombol Tambah Habit](screenshots/tambah_habit1.png)

**b. Coba simpan tanpa mengisi nama (validasi muncul).**

![Validasi Kosong](screenshots/tambah_habit2.png)

**c. Isi form dan simpan. Habit muncul di daftar.**

![Habit Ditambahkan](screenshots/tambah_habit2.png)

---

### ✏️ 4. Uji Edit Habit

**a. Klik menu tiga titik pada habit, pilih "Edit".**
![Edit Habit](screenshots/edit_habit1.png)

**b. Form edit muncul dengan data yang sudah ada.**
![Edit Habit](screenshots/edit_habit2.png)

**c. Edit data lalu simpan. Perubahan tampil di list.**
![Edit Habit](screenshots/edit_habit3.png)

---

### 🗑️ 5. Uji Hapus Habit

**a. Klik menu tiga titik, pilih "Hapus".**
![Konfirmasi Hapus](screenshots/hapus_habit1.png)

**b. Dialog konfirmasi muncul. Klik batal.**
![Konfirmasi Hapus](screenshots/hapus_habit2.png)

**c. Coba hapus lagi dan klik "Hapus". Habit hilang.**
![Konfirmasi Hapus](screenshots/hapus_habit3.png)

---

### 📊 6. Uji Progress Bar

Progress bar di AppBar berubah setelah centang, tambah, atau hapus habit.

**a. Tambah**
![Progress Bar](screenshots/progressbar1.png)

**b. Centang**
![Progress Bar](screenshots/progressbar2.png)

**c. Hapus**
![Progress Bar](screenshots/progressbar3.png)

---

### 🔄 7. Uji Reset

Tombol "Reset" mengembalikan semua `isDone` menjadi false.

![Reset Habit](screenshots/reset.png)

---

### 🔁 8. Uji Ephemeral State

Tutup aplikasi dan buka kembali. Semua data kembali ke default dari `habits.json`.

![Ephemeral State](screenshots/flutter_run.png)

---
