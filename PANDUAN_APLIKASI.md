# Panduan Penggunaan Aplikasi "Elfoody" - Perencana Menu & Rincian Belanja

Aplikasi web modern berbasis Single Page Application (SPA) untuk merencanakan menu masak keluarga sehari-hari dan otomatis menghasilkan rincian belanja mingguan.

---

## 🎨 Tema & Tampilan Visual
- **Palet Warna Lembut**: *Cream* hangat (`#FAF7F2`, `#FAF6EE`), *Taupe* anggun (`#8D7B68`, `#5C4E3F`), sentuhan *Warm White*, serta aksen *Soft Sage Green* dan *Terracotta*.
- **Desain Bersih & Elegan**: Tipografi modern (*Plus Jakarta Sans* & aksen *Playfair Display*), sudut melengkung halus (*rounded-3xl*), bayangan lembut, dan responsif untuk layar laptop/PC maupun smartphone/tablet.

---

## 🌟 5 Fitur Utama Sesuai Kebutuhan

### 1. Halaman Utama (Papan Menu Pertanggal)
- **Menu Hari Ini (Default)**: Langsung menampilkan menu yang dijadwalkan untuk hari ini lengkap dengan 6 pilar gizi, bahan baku, porsi, serta status kesiapan masak.
- **Tampilan Minggu Ini (Bisa Digeser / Swipeable)**: 
  - Tampilan kartu 7 hari (Senin - Minggu) dalam format *deck carousel* horizontal.
  - Dapat digeser dengan mudah (swipe pada layar sentuh atau klik tombol panah / drag pada mouse).
  - Hari ini ditandai khusus dengan label emas **HARI INI**.
  - Dilengkapi tombol ganti pekan (*Minggu Sebelumnya* / *Minggu Berikutnya*).

### 2. Fitur "ISI MENU" (Pengaturan Jadwal H-2 & Tukar Menu)
- **Aturan Minimal H-2**: 
  - Pengisian dan perubahan menu langsung hanya diizinkan untuk hari yang berjarak **minimal 2 hari ke depan (H-2)** dari hari ini agar belanja dan persiapan masak terencana rapi.
  - Jika tanggal yang dipilih kurang dari H-2, sistem akan menampilkan penanda terkunci dan tombol jalan keluar: **Tukar Menu**.
  - *(Tersedia juga opsi "Mode Simulasi Edit" jika ingin menguji pengubahan langsung).*
- **Fitur Tukar Menu Antar Hari**:
  - Menu dapat ditukar kapan saja dengan catatan **berada dalam minggu yang sama (Senin - Minggu)**.
  - Memudahkan jika tiba-tiba ingin menukar menu hari ini dengan hari esok atau hari lain di pekan tersebut.
- **2 Metode Pengisian**:
  1. **Menu Paket**: Cukup pilih paket menu komplit yang sudah dirancang sebelumnya (1 kali klik langsung mengisi 6 pilar gizi).
  2. **Menu Satuan**: Pilih hidangan satuan per kategori nutrisi dari katalog makanan.

### 3. "DAPUR GIZI & BAHAN" (Kategori Kandungan Gizi & Master Belanja)
*(Nama baru yang lebih menarik & profesional dari menu "Pengisian Kategori Perkandungan Gizi")*
- Dikelompokkan ke dalam **6 Kategori Gizi Seimbang**:
  1. 🍚 **Karbohidrat** (Nasi putih, nasi uduk, nasi merah, kentang panggang, ubi, dll.)
  2. 🍗 **Protein** (Ayam lengkuas, ikan bakar, bacem tempe tahu, sapi lada hitam, telur balado, dll.)
  3. 🥦 **Serat Sayur** (Sayur asem, tumis kangkung terasi, sup sayur bening, capcay, dll.)
  4. 🍎 **Serat Buah** (Semangka, pepaya California, pisang ambon, melon madu, dll.)
  5. 🌶️ **Tambahan** (Sambal terasi dadak, kerupuk udang, lalapan kemangi, tempe mendoan, dll.)
  6. 🍮 **Dessert** (Kolak pisang ubi, pudding cokelat susu, es kuwut jeruk nipis, dll.)
- **Fitur Pengisian Daftar Belanja per Menu**:
  - Setiap masakan memiliki rincian bahan belanja (nama bahan, takaran/jumlah, satuan, dan kelompok pasarnya).
  - Data bahan ini menjadi sumber otomatis untuk menghitung daftar belanja mingguan.

### 4. "PAKET MENU" (Perencanaan Paket Siap Pakai)
- Fitur untuk menggabungkan hidangan dari Dapur Gizi menjadi paket komplit yang lezat dan seimbang.
- Tersedia paket bawaan (Paket Selera Nusantara Sunda, Paket Ikan Bakar Komplit, Paket Sehat Rendah Kalori, Paket Daging Lada Hitam).
- Anda dapat membuat paket kustom baru sesuka hati dan langsung menerapkannya ke tanggal mana pun di *Isi Menu*.

### 5. "RINCIAN BELANJA" (Otomasi Belanja Jumat ke Jumat & Belanja Stok)
- **Siklus Belanja Hari Jumat**:
  - Otomatis menghitung dan menampilkan daftar bahan belanja untuk periode masak **Sabtu besok sampai Jumat depan (7 hari ke depan)**.
  - Tersedia pilihan melihat siklus Jumat ini maupun Jumat berikutnya.
- **✨ Fitur Baru: Tambah Belanja Stok Manual**:
  - Kini Anda bisa menambahkan barang belanjaan di luar menu masak yang terjadwal (misal: minyak goreng cadangan, sabun cuci, beras tambahan, bumbu stok bulanan).
  - Dilengkapi tombol **+ Tambah Belanja Stok** di bagian atas daftar belanja dan pada tampilan kosong.
  - Menampilkan badge **📦 Stok**, kolom jumlah, satuan, kelompok belanja, dan catatan keperluan.
  - Dapat dicentang saat berbelanja, dihapus kapan saja dengan konfirmasi aman, dan otomatis masuk ke dalam salinan WhatsApp & cetak PDF.
- **✨ 18 Rekomendasi Satuan Populer**:
  - Dilengkapi 18 pilihan satuan standar siap klik di semua form bahan & stok:
    `gram`, `potong`, `Sdm`, `Sdt`, `Ikat`, `Buah`, `Pcs`, `Siung`, `Lembar`, `Butir`, `Batang`, `ml`, `sachet`, `bungkus`, `helai`, `cm`, `papan`, `porsi`.
- **Pengelompokan Otomatis Menurut Area Pasar/Supermarket**:
  - 🥩 *Daging & Unggas*
  - 🥬 *Sayur Mayur Segar*
  - 🍎 *Buah-buahan*
  - 🧄 *Bumbu*
  - 🌿 *Rempah*
  - 🍶 *Sauce*
  - 🌾 *Tepung*
  - 🧺 *Lainnya*
  - 🍮 *Dessert*
- **Fitur Praktis Saat Belanja**:
  - **Checklist Interaktif**: Centang bahan yang sudah dibeli (progres belanja naik otomatis).
  - **Keterangan Menu Terkait**: Setiap bahan menampilkan informasi masakan atau catatan stok.
  - **Salin ke WhatsApp**: 1 klik untuk menyalin seluruh daftar belanja terformat rapi dengan checklist dan emoji untuk dikirim ke chat WhatsApp.
  - **Cetak / PDF**: Format cetak bersih siap cetak ke kertas atau simpan sebagai PDF.

---

## 🌐 DEPLOY OTOMATIS VERCEL & GITHUB

Aplikasi kini telah dialihkan ke **Vercel** yang terhubung langsung dengan repositori GitHub:
👉 **Repository GitHub**: `https://github.com/indriatisyahputri/Elfoody`
👉 **Deploy Vercel**: Otomatis diperbarui setiap kali ada perubahan yang di-push ke GitHub.

- **Sinkronisasi Cloud Real-Time**: Data tersinkronisasi 24/7 di semua perangkat (iPhone, HP Suami, Laptop/PC) via Cloud KVDB.
- **Push Pembaruan 1-Klik**: Cukup klik dua kali file `Push-Update-ke-GitHub.bat` di folder utama untuk otomatis commit dan push ke GitHub & Vercel.
- **PWA & Tampilan Layar Penuh di iPhone**:
  1. Buka link di **Safari** iPhone.
  2. Ketuk ikon **Bagikan (Share)** (kotak dengan panah ke atas).
  3. Pilih **"Add to Home Screen" (Tambah ke Layar Utama)**.
  4. Aplikasi akan tampil di layar utama seperti aplikasi bawaan iPhone dan berjalan layar penuh (*full screen*) tanpa bilah browser Safari!

### C. Penyimpanan Data
- Seluruh data menu, masakan baru, dan centang belanja tersimpan aman secara otomatis di browser (*localStorage*), sehingga tidak akan hilang saat halaman ditutup atau di-refresh.
