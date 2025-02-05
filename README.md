# Proyek Game Kuis Mobile TrashMaster (Edukatif)


## Checklist Pengembangan Aplikasi

### 1️⃣ Desain dan Struktur Aplikasi
- [ ] Tentukan tampilan utama aplikasi (MainActivity) dan layout kuis
- [ ] Rancang tampilan kuis dengan timer, pilihan ganda, dan feedback jawaban
- [ ] Tentukan kategori dan level kesulitan kuis (edukasi lingkungan)
- [ ] Buat desain dan UI/UX (animasi transisi soal, feedback visual jawaban)
- [ ] Buat struktur navigasi aplikasi (menu, login, leaderboard, kuis, dsb)

### 2️⃣ Implementasi Fitur Utama

#### Kuis & Pengguna
- [ ] Implementasikan Firebase Authentication untuk login pengguna
- [ ] Buat sistem XP yang bisa digunakan untuk membeli hint
- [ ] Tambahkan penentuan level kesulitan berdasarkan XP
- [ ] Buat sistem notifikasi untuk pengingat challenge dan reset leaderboard mingguan

#### Sistem Kuis
- [ ] Desain dan implementasikan mode permainan pilihan ganda dengan batas waktu tertentu
- [ ] Buat feedback visual untuk jawaban benar/salah
- [ ] Tambahkan fitur leaderboard online
- [ ] Integrasikan Firestore Database untuk menyimpan data pertanyaan kuis dan progres pemain

#### Mini-Game
##### Game Menyusun Sampah
- [ ] Implementasikan drag and drop dengan Canvas API
- [ ] Tambahkan poin dan XP untuk jawaban benar/salah

##### Game Menangkap Sampah
- [ ] Implementasikan objek jatuh dan kontrol untuk menangkap dengan wadah yang sesuai
- [ ] Berikan penalti jika menangkap sampah di wadah yang salah

### 3️⃣ Integrasi dan Pengujian
- [ ] Integrasi Realtime Database Firebase untuk multiplayer dan leaderboard
- [ ] Tes dan optimalkan kuota baca/tulis di Realtime Database agar tidak cepat habis kuota
- [ ] Uji aplikasi secara menyeluruh untuk stabilitas dan bug
- [ ] Tes fitur multiplayer: tantangan dengan teman dan player random

### 4️⃣ Peluncuran dan Update
- [ ] Buat notifikasi untuk pengingat dan update leaderboard mingguan
- [ ] Lakukan pengujian beta untuk feedback pengguna (terutama pelajar SD)
- [ ] Perbaiki dan optimalkan aplikasi berdasarkan masukan
- [ ] Persiapkan publish ke Google Play Store

---

## Checklist Pengembangan Fitur:

1. **Mode Permainan**
   - [ ] Pilihan ganda
   - [ ] Mode waktu
   - [ ] Mode turnamen

2. **Kategori dan Level**
   - [ ] Semua level
   - [ ] Sistem XP dan Grinding

3. **Sistem Skor dan Reward**
   - [ ] Poin untuk jawaban benar
   - [ ] Bonus streak
   - [ ] XP untuk membuka fitur dan pertanyaan baru

4. **Desain UI/UX**
   - [ ] Animasi transisi soal
   - [ ] Feedback visual untuk jawaban benar/salah

5. **Fitur Tambahan**
   - [ ] Multiplayer (tantangan dengan teman atau random)
   - [ ] Leaderboard online
   - [ ] Integrasi dengan Firebase
   - [ ] Notifikasi pengingat challenge atau reset leaderboard mingguan

---


## Ringkasan Struktur Modular

### **Activity Layouts:**
- [ ] SplashScreenActivity
- [ ] MainActivity
- [ ] KuisActivity
- [ ] LeaderboardActivity
- [ ] ProfileActivity
- [ ] ChallengeActivity
- [ ] SettingsActivity

### **Helper Classes:**
- [ ] **FirebaseHelper**: Menangani operasi Firebase (misal simpan XP/level).
- [ ] **SQLiteHelper**: Menangani operasi SQLite (misal simpan XP/level lokal).
