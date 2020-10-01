# Apa itu Container dan Docker?
Container sesuai namanya adalah sesuatu yang berisi atau menyimpan (contain). Dalam kasus ini, Container adalah sebuah unit yang berisi sebuah program. Container memungkinkan sebuah program dijalankan tanpa konfigurasi yang membingungkan dan rawan kesalahan. Salah satu teknologi Container yang populer adalah Docker. Docker merupakan platform terpadu untuk membuat, menjalankan, dan membagikan Container.

# Komponen Docker
Ada 3 komponen dalam Docker untuk membuat, menjalankan, dan membagikan Container yaitu: **Docker Engine**, **Dockerfile**, dan **Docker Hub**. Docker Engine adalah aplikasi *client-server* yang menjalankan segala proses terkait Container. Docker Engine membentuk sebuah Container menurut Docker Image. Dockerfile adalah sebuah berkas yang menginstruksikan Docker Engine membuat Docker Image. Docker Hub adalah tempat untuk menyimpan serta membagikan Docker Image.

# Apa yang akan saya lakukan?
Anda akan berkontribusi dengan membuat sebuah (atau beberapa) Dockerfile berisi web framework yang bisa digunakan untuk keperluan pengembangan. Dengan berkontribusi di sini, Anda diharapkan dapat belajar tentang Docker (Docker Engine, Dockerfile), *open source*, dan GitHub. Anda juga dapat menjadikan kontribusi Anda di sini untuk berpartisipasi dalam **Hacktoberfest 2020**.

# Kontribusi yang Diharapkan
* Port Container yang dibuka sesuai dengan pengaturan *default* web framework yang Anda pilih (Contoh: Django -> Port 8000)
* Dockerfile dan berkas lainnya dimasukkan ke dalam satu folder dengan format **NAMAFRAMEWORK_OPERATINGSYSTEM**

# Bagaimana saya memulai?
1. Pasang Docker di sistem Anda. Anda bisa mengikuti instruksi resmi Docker di https://docs.docker.com/get-docker/.
2. *Clone*/Unduh repositori ini ke sisem Anda.
3. Buat Docker Image contoh (Django) dengan *command*
```
docker build -t NAMA_BEBAS_SILAKAN_DIGANTI
```
4. Jalankan Docker Image yang sudah dibuat dengan *command*
```
docker run NAMA_BEBAS_SILAKAN_DIGANTI -d -p 80:8000
```
5. Akses Container dengan browser menunjuk ke alamat **localhost:80**.

# Bagaimana saya berkontribusi?
1. *Fork* repositori ini ke akun Anda.
2. Buatlah Dockerfile yang belum ada di repositori ini.
3. Buatlah *pull request*.

# Bagaimana kalau saya butuh bantuan?
Google/Bing/DuckDuckGo dan Stack Overflow adalah teman terbaik Anda. Namun jika Anda benar-benar buntu, silakan menghubungi @liehart,@danes44,@debugvelop di Telegram.

# Referensi
https://hacktoberfest.digitalocean.com/
https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github
https://docs.docker.com/get-started/
https://www.djangoproject.com/start/
https://docs.docker.com/engine/reference/builder/
