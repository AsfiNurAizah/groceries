# Deployment ke Vercel

Aplikasi React JS ini di-deploy menggunakan Vercel, sebuah platform hosting cloud yang menyediakan deployment otomatis dan skalabilitas yang baik. Berikut adalah langkah-langkah yang dilakukan untuk men-deploy aplikasi ini ke Vercel.

## Prasyarat

- Memiliki akun di Vercel (https://vercel.com)
- Repositori GitHub yang berisi kode aplikasi React JS

## Langkah-langkah Deployment

1. **Integrasi dengan Vercel**
   - Masuk ke akun Vercel Anda.
   - Klik tombol "New Project" di sudut kanan atas dashboard.
   - Pilih opsi "Import Git Repository" dan masukkan URL repositori GitHub yang berisi kode aplikasi React JS Anda.
   - Vercel akan secara otomatis mendeteksi bahwa itu adalah proyek React dan menyediakan pengaturan build yang sesuai.

2. **Konfigurasi Pipeline Deployment**
   - Setelah Vercel mendeteksi proyek, Anda dapat mengonfigurasi pipeline deployment.
   - Pilih cabang (branch) yang ingin Anda deploy, misalnya `main` atau `master`.
   - Anda juga dapat mengonfigurasi pengaturan lanjutan seperti environment variables atau alat pembangunan (build tools) yang digunakan.

3. **Deployment Aplikasi**
   - Setelah melakukan konfigurasi, klik tombol "Deploy" untuk memulai proses deployment.
   - Vercel akan membangun (build) dan men-deploy aplikasi React JS Anda.
   - Anda dapat melihat status deployment di dashboard Vercel.

4. **Akses Aplikasi yang Di-deploy**
   - Setelah proses deployment selesai, Vercel akan memberikan URL default seperti `https://your-project-name.vercel.app` untuk mengakses aplikasi yang sudah di-deploy.
   - Anda juga dapat mengonfigurasi custom domain di pengaturan proyek Vercel untuk menggunakan domain yang lebih mudah diingat.

5. **Integrasi Berkelanjutan**
   - Setiap kali Anda melakukan commit dan push perubahan ke cabang yang dikonfigurasi (misalnya `main` atau `master`), Vercel akan secara otomatis membangun dan men-deploy versi terbaru aplikasi Anda.
   - Ini memungkinkan proses deployment yang cepat dan efisien setiap kali ada perubahan di kode aplikasi.

## Konfigurasi Tambahan

- **Environment Variables**: Anda dapat menambahkan environment variables yang diperlukan oleh aplikasi Anda di pengaturan proyek Vercel. Ini berguna untuk menyimpan informasi sensitif seperti kunci API atau kredensial database.

- **Build Settings**: Jika proyek Anda memerlukan pengaturan build khusus, Anda dapat mengonfigurasinya di bagian "Build & Development Settings" di pengaturan proyek Vercel.

- **Deployment Hooks**: Vercel juga menyediakan deployment hooks yang memungkinkan Anda untuk memicu deployment baru dari sistem eksternal atau alat integrasi berkelanjutan lainnya.

Dengan mengikuti langkah-langkah ini, Anda dapat dengan mudah men-deploy aplikasi React JS ke Vercel dan membuatnya dapat diakses secara publik. Vercel menyediakan fitur-fitur seperti deployment otomatis, skalabilitas, dan integrasi Git yang sangat membantu dalam proses pengembangan dan deployment aplikasi modern.
