# TrashMaster - Game Kuis Mobile Edukatif

## Deskripsi Proyek
TrashMaster adalah aplikasi kuis mobile yang bertujuan untuk memberikan edukasi tentang pentingnya menjaga lingkungan melalui permainan kuis dan mini-game yang interaktif. Aplikasi ini dirancang untuk pelajar SD dengan tujuan meningkatkan kesadaran lingkungan melalui edukasi yang menyenangkan dan menantang.

### Fitur Utama:
- **Mode Permainan**: Pilihan ganda dengan timer dan mode turnamen
- **Sistem XP dan Level**: Gunakan XP untuk membeli hint dan membuka level kesulitan baru
- **Mini-Game Edukatif**: Game menyusun dan menangkap sampah untuk memberi edukasi yang menyenangkan
- **Leaderboard Online**: Kompetisi dengan pemain lain
- **Firebase Integration**: Menyimpan data pengguna dan progres kuis
- **Multiplayer**: Tantangan dengan teman atau pemain acak
---

## Checklist Pengembangan Aplikasi

### 1️⃣ Desain dan Struktur Aplikasi
- [ ] Tentukan tampilan utama aplikasi (MainActivity) dan layout untuk kuis
- [ ] Rancang tampilan kuis dengan timer, pilihan ganda, dan feedback untuk jawaban
- [ ] Tentukan kategori dan level kesulitan untuk kuis (edukasi tentang lingkungan)
- [ ] Buat desain UI/UX yang menarik (animasi transisi soal dan feedback visual jawaban)
- [ ] Rancang struktur navigasi aplikasi (menu, login, leaderboard, kuis, dsb)

### 2️⃣ Implementasi Fitur Utama

#### Kuis & Pengguna
- [ ] Implementasikan Firebase Authentication untuk login pengguna
- [ ] Buat sistem XP yang bisa digunakan untuk membeli hint
- [ ] Tentukan level kesulitan berdasarkan XP
- [ ] Buat sistem notifikasi untuk pengingat challenge dan reset leaderboard mingguan

#### Sistem Kuis
- [ ] Desain dan implementasikan mode permainan pilihan ganda dengan batas waktu tertentu
- [ ] Buat feedback visual yang menunjukkan jawaban benar/salah
- [ ] Tambahkan fitur leaderboard online
- [ ] Gunakan Firestore Database untuk menyimpan data soal dan progres pemain

#### Mini-Game
##### Game Menyusun Sampah
- [ ] Implementasikan drag and drop dengan Canvas API
- [ ] Tambahkan poin dan XP untuk jawaban yang benar/salah

##### Game Menangkap Sampah
- [ ] Buat objek yang jatuh dan kontrol untuk menangkap dengan wadah yang sesuai
- [ ] Berikan penalti jika menangkap sampah di wadah yang salah

### 3️⃣ Integrasi dan Pengujian
- [ ] Integrasi Realtime Database Firebase untuk multiplayer dan leaderboard
- [ ] Tes dan optimalkan kuota baca/tulis di Realtime Database supaya tidak cepat habis
- [ ] Lakukan pengujian menyeluruh untuk stabilitas dan bug
- [ ] Uji fitur multiplayer: tantangan dengan teman atau pemain acak

### 4️⃣ Peluncuran dan Update
- [ ] Buat notifikasi untuk pengingat dan update leaderboard mingguan
- [ ] Lakukan pengujian beta untuk mendapatkan feedback dari pengguna (terutama pelajar SD)
- [ ] Perbaiki dan optimalkan aplikasi berdasarkan masukan dari pengguna
- [ ] Persiapkan untuk dipublikasikan di Google Play Store

---

## Checklist Pengembangan Fitur:

1. **Mode Permainan**
   - [ ] Pilihan ganda
   - [ ] Mode dengan batas waktu
   - [ ] Mode turnamen

2. **Kategori dan Level**
   - [ ] Semua level kesulitan
   - [ ] Sistem XP dan grinding

3. **Sistem Skor dan Reward**
   - [ ] Poin untuk jawaban benar
   - [ ] Bonus streak untuk jawaban benar berturut-turut
   - [ ] XP yang bisa digunakan untuk membuka fitur atau pertanyaan baru

4. **Desain UI/UX**
   - [ ] Animasi transisi soal
   - [ ] Feedback visual untuk jawaban benar/salah

5. **Fitur Tambahan**
   - [ ] Multiplayer (tantangan dengan teman atau pemain random)
   - [ ] Leaderboard online
   - [ ] Integrasi dengan Firebase
   - [ ] Notifikasi untuk pengingat challenge atau reset leaderboard mingguan

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
- [ ] **FirebaseHelper**: Untuk mengelola operasi Firebase (misalnya menyimpan XP/level).
- [ ] **SQLiteHelper**: Untuk mengelola operasi SQLite (misalnya menyimpan XP/level lokal).
