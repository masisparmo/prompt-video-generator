# **Video Prompt Generator Powered by Gemini Ai**

## **1\. Pendahuluan**

**Panduan & Penghasil Prompt Veo** adalah sebuah aplikasi web interaktif yang dirancang untuk membantu para kreator konten, pemasar, dan siapa saja yang ingin membuat video pendek menggunakan model AI generatif seperti Google Veo.

Tujuan utama aplikasi ini adalah untuk menyederhanakan proses _prompt engineering_ (rekayasa prompt). Aplikasi ini mampu mengubah ide sederhana dari pengguna menjadi sebuah _prompt_ yang detail, terstruktur, dan efektif, dengan fokus pada penciptaan konten yang memiliki nuansa khas Indonesia. Dengan bantuan asisten AI (Gemini), proses kreatif menjadi lebih cepat, mudah, dan inspiratif.

## **2\. Penjelasan Fitur**

Aplikasi ini dilengkapi dengan beberapa fitur utama untuk memaksimalkan pengalaman Anda:

#### **a. Pengaturan API Key Gemini**

Untuk menggunakan fitur cerdas, aplikasi ini memerlukan koneksi ke model AI Google, Gemini.

- **Input API Key:** Anda harus memasukkan kunci API pribadi Anda untuk mengaktifkan fitur-fitur yang ditenagai oleh AI.
- **Panduan Interaktif:** Terdapat panduan singkat yang bisa dibuka-tutup (accordion) yang menjelaskan langkah-langkah untuk mendapatkan API Key dari Google AI Studio.

#### **b. ✨ Kembangkan Ide dengan AI**

Ini adalah fitur unggulan yang berfungsi sebagai asisten kreatif Anda.

- **Input Ide Sederhana:** Anda cukup memasukkan ide dasar dalam satu kalimat (contoh: "anak-anak bermain layangan di pantai").
- **Pengembangan Otomatis:** Dengan menekan tombol **"Kembangkan Ide dengan AI"**, aplikasi akan mengirim ide Anda ke Gemini. AI kemudian akan mengembangkannya menjadi konsep yang lebih kaya, menyarankan deskripsi adegan, subjek utama, latar belakang, dan dialog yang lebih hidup dalam **Bahasa Indonesia**.
- **Pengisian Otomatis:** Hasil dari AI akan langsung mengisi kolom-kolom yang relevan pada formulir, siap untuk Anda sempurnakan.

#### **c. Pembuatan Prompt Manual yang Terstruktur**

Anda memiliki kendali penuh untuk membuat atau menyempurnakan _prompt_ secara manual.

- **Formulir Lengkap:** Tersedia kolom-kolom terstruktur seperti "Gaya Visual", "Gerakan Kamera", "Subjek Utama", "Latar Belakang", "Palet Warna", dan "Dialog / Suara Latar".
- **Pilihan Sinematik:** Opsi-opsi pada menu _dropdown_ (seperti "Sinematik", "Slow pan", "Warna hangat") membantu Anda menambahkan detail teknis dengan mudah tanpa harus menghafal istilah-istilah sinematografi.

#### **d. Hasil Prompt Ganda (Bilingual)**

Setelah semua detail siap, aplikasi akan menghasilkan _prompt_ dalam dua format bahasa.

- **Dua Jendela Terpisah:** _Prompt_ dalam Bahasa Indonesia dan Bahasa Inggris ditampilkan secara berdampingan dalam jendela terpisah agar mudah dibaca dan dibandingkan.
- **Terjemahan Otomatis:** Aplikasi secara otomatis menerjemahkan detail-detail yang Anda masukkan ke dalam Bahasa Inggris yang natural menggunakan Gemini, memastikan _prompt_ versi Inggris juga akurat dan efektif.
- **Area Gulir (Scroll Bar):** Setiap jendela hasil memiliki _scroll bar_ sendiri, sehingga tampilan tetap rapi meskipun _prompt_ yang dihasilkan sangat panjang.

#### **e. Notifikasi dan Umpan Balik**

Aplikasi memberikan umpan balik visual untuk setiap aksi.

- **Notifikasi Error:** Jika API Key salah atau terjadi masalah saat menghubungi AI, sebuah pesan error yang jelas akan muncul.
- **Indikator Proses:** Tombol akan menampilkan ikon _spinner_ (berputar) saat AI sedang memproses permintaan Anda.
- **Konfirmasi "Tersalin":** Tombol "Salin" akan berubah warna dan teks menjadi "Tersalin!" sebagai konfirmasi bahwa teks berhasil disalin ke _clipboard_.

## **3\. Cara Penggunaan**

Berikut adalah panduan langkah demi langkah untuk menggunakan aplikasi ini:

#### **Langkah 1: Masukkan API Key Anda**

- Pertama kali, dapatkan **Gemini API Key** Anda dari [Google AI Studio](https://aistudio.google.com/).
- Klik pada tulisan "Bagaimana cara mendapatkan API Key?" di aplikasi untuk melihat petunjuknya.
- Salin dan tempel kunci tersebut ke dalam kolom **"Gemini API Key Anda"**. Ini hanya perlu dilakukan sekali per sesi.

#### **Langkah 2: Tuliskan Ide Dasar Anda**

- Pada kolom **"Ide Sederhana / Deskripsi Adegan"**, ketikkan konsep dasar video yang ingin Anda buat. Usahakan sesederhana mungkin.
  - _Contoh:_ seorang kakek sedang membatik

#### **Langkah 3 (Opsional tapi Direkomendasikan): Gunakan Asisten AI**

- Klik tombol ungu **"✨ Kembangkan Ide dengan AI"**.
- Tunggu beberapa saat sementara AI memproses ide Anda.
- Perhatikan bagaimana kolom "Deskripsi Adegan", "Subjek Utama", "Latar Belakang", dan "Dialog" akan terisi secara otomatis dengan deskripsi yang lebih kaya dalam Bahasa Indonesia.
  - _Contoh hasil AI:_
    - **Deskripsi Adegan:** Seorang kakek tua dengan sabar melukis motif batik yang rumit pada selembar kain putih menggunakan canting di sebuah pendopo Jawa yang tenang.
    - **Subjek Utama:** Kakek berusia 70-an, mengenakan kemeja surjan lurik dan blangkon, wajahnya menunjukkan konsentrasi penuh.
    - **Latar Belakang:** Pendopo kayu dengan ukiran gebyok, beberapa kain batik lain tergantung di latar belakang, cahaya sore yang hangat masuk dari samping.
    - **Dialog / Suara Latar:** (Tidak ada dialog) Suara gamelan Jawa yang mengalun lembut, gesekan canting pada kain.

#### **Langkah 4: Sempurnakan Detail**

- Tinjau kembali semua kolom yang telah terisi. Anda bisa mengubah atau menambahkan detail sesuai keinginan.
- Pilih **"Gaya Visual"**, **"Gerakan Kamera"**, dan **"Palet Warna"** dari menu _dropdown_ yang tersedia.

#### **Langkah 5: Hasilkan Prompt Final**

- Setelah semua detail terasa pas, klik tombol biru **"Hasilkan Prompt Efektif"**.
- Aplikasi akan memproses semua masukan, termasuk menerjemahkannya ke Bahasa Inggris.

#### **Langkah 6: Salin dan Gunakan Prompt Anda**

- Di sisi kanan, Anda akan melihat dua jendela hasil.
- Gunakan tombol **"Salin Prompt ID"** untuk menyalin versi Bahasa Indonesia, atau **"Salin Prompt EN"** untuk versi Bahasa Inggris.
- Tempelkan _prompt_ yang telah disalin ke platform video AI (seperti Google Vids atau lainnya) untuk membuat video Anda.

Selamat berkreasi!
