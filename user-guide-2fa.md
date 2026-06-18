# [Sampel Portofolio] Panduan Pengguna: Mengaktifkan Autentikasi 2 Langkah (2FA)

**Kategori:** User Documentation / Keamanan  
**Format:** Markdown  
**Target Pembaca:** Pengguna umum (Non-teknis) yang ingin mengamankan akun mereka.  

---

Autentikasi 2 Langkah (2FA) memberikan lapisan keamanan ekstra pada akun Anda. Setelah fitur ini aktif, Anda wajib memasukkan kode verifikasi 6 digit dari aplikasi ponsel Anda setiap kali melakukan login, selain menggunakan kata sandi biasa.

## Prasyarat
Sebelum memulai proses aktivasi, pastikan Anda telah mengunduh salah satu aplikasi otentikator berikut di ponsel Anda:
* Google Authenticator ([Android](https://play.google.com) / [iOS](https://apps.apple.com))
* Twilio Authy

---

## Langkah 1: Buka Pengaturan Keamanan Akun
1. Masuk (*Login*) ke akun Anda melalui browser.
2. Klik **Foto Profil** Anda di pojok kanan atas layar, lalu pilih **Pengaturan Akun**.
3. Pada menu navigasi di sisi kiri, klik tab **Keamanan**.

## Langkah 2: Mulai Aktivasi 2FA
1. Gulir ke bawah hingga Anda menemukan bagian **Autentikasi 2 Langkah**.
2. Klik tombol **Aktifkan Autentikasi**.
3. Demi keamanan, sistem akan meminta Anda untuk memasukkan kembali **Kata Sandi (Password)** Anda saat ini. Masukkan kata sandi, lalu klik **Lanjutkan**.

## Langkah 3: Pindai Kode QR
Di layar komputer Anda akan muncul sebuah **Kode QR** unik beserta kunci rahasia teks (*Secret Key*).

1. Buka aplikasi **Google Authenticator** di ponsel Anda.
2. Ketuk ikon **tanda plus (+)** di pojok kanan bawah aplikasi.
3. Pilih **Pindai kode QR** (*Scan a QR code*).
4. Arahkan kamera ponsel Anda ke Kode QR yang ada di layar komputer.
5. Aplikasi akan otomatis memunculkan akun baru dengan 6 digit angka yang berubah setiap 30 detik.

## Langkah 4: Verifikasi Kode
1. Kembali ke layar komputer Anda, klik **Lanjutkan**.
2. Masukkan 6 digit angka yang saat ini tampil di aplikasi Google Authenticator Anda ke dalam kolom verifikasi yang tersedia.
3. Klik **Verifikasi & Selesai**.

---

## ⚠️ PENTING: Simpan Kode Cadangan (Backup Codes)
Setelah berhasil mengaktifkan 2FA, sistem akan menampilkan **10 Kode Cadangan**. 

* **Unduh atau catat** kode-kode tersebut dan simpan di tempat yang aman (jangan di dalam ponsel yang sama).
* **Fungsi:** Kode ini adalah satu-satunya cara untuk masuk ke akun Anda jika ponsel Anda hilang, rusak, atau terformat. Setiap kode hanya bisa digunakan satu kali.
