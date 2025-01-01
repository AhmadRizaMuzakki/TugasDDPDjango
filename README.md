# TugasDDPDjango

1. Membuat Virtual Environment
Pertama, buat virtual environment baru untuk proyek Anda. Ini membantu menjaga dependensi proyek tetap terisolasi.

bash
python3 -m venv myenv
2. Mengaktifkan Virtual Environment
Aktifkan virtual environment yang baru dibuat.

Di Windows:

bash
myenv\Scripts\activate
Di macOS/Linux:

bash
source myenv/bin/activate
3. Menginstal Django
Setelah virtual environment aktif, instal Django menggunakan pip.

bash
pip install django
4. Membuat Proyek Django Baru
Buat proyek Django baru dengan perintah django-admin.

bash
django-admin startproject myproject
5. Menavigasi ke Direktori Proyek
Pindah ke direktori proyek yang baru dibuat.

bash
cd myproject
6. Menjalankan Server Pengembangan
Jalankan server pengembangan Django untuk memastikan proyek terinstal dengan benar.

bash
python manage.py runserver
7. Membuat Aplikasi Baru
Buat aplikasi baru di dalam proyek Anda.

bash
python manage.py startapp myapp
