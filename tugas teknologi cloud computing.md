NAMA    : Abdul Azis
NIM     : 095410176
JURUSAN : TI

Tugas Tengah Semester

I. Jelaskan secara singkat istilah-istilah berikut ini (nilai 20):
    a. Unikernel
    b. Dockerfile
    c. Docker Hub
    d. dockerd
    e. XaaS
II. Jawab pertanyaan berikut ini dengan singkat (nilai 30):
    Jelaskan fungsi dan keterkaitan antara Docker-CE dengan DockerCompose.
III. Kasus (nilai 50):
    Jelaskan image docker milik anda yang ada di Docker Hub.

Jawaban

I.  a. Unikernel: Sebuah Virtual Machine yang memiliki satu Bahasa dan satu fungsi yang digunakan pada environment yang minimal.
    b. Dockerfile: script yang yang berisi dari serangkaian perintah yang akan dieksekusi secara otomatis dan berurutan untuk membuat sebuah image.
    c. Docker Hub: Tempat penyimpanan public di mana developer dapat mengunggah dan mengunduh image.
    d. Dockerd: Proses yang terus-menerus untuk mengelola kontainer Docker dan menangani objects container.
    e. XaaS: Sejumlah layanan yang dikirimkan melalui Internet

II. Docker-CE : Docker Community Edition adalah varian dari Docker yang diperuntukkan untuk developers dan small teams yang baru memulai menggunakan Docker dan melalukan experimenting dengan container-based apps. 
    DockerCompose: Berfungsi untuk menjalankan container docker secara bersamaan.

    Jadi untuk menajalankan Docker-CE dibutuhkan Docker-Compose.

III. Image docker dalam docker hub telah sedikit dimodifikasi beberapa configurasinya dan ditambahkan beberapa tool didalamnya. 


Tugas Akhir Semester

I. Jelaskan secara singkat istilah-istilah berikut ini (nilai 20):
    a. Kubernetes
    b. kubectl
    c. pod
    d. docker compose
    e. docker machine
II. Jawab pertanyaan berikut ini dengan singkat (nilai 30):
    a. Apakah Basic Objects dari Kubernetes itu?
    b. Apakah Controllers itu?
    c. Jelaskan keterkaitan antara Basic Objects dengan Controllers.
III. Kasus (nilai 50):
     Berikan contoh deployment pod dengan menggunakan perintah kubectl. Image container harus ada (bisa anda buat sendiri atau mencari di Internet, tetapi harus bisa diakses / berada di DockerHub).Jelaskan juga cara mengakses aplikasi yang anda deploy tersebut.

Jawaban

I.  a. Kubernetes: Platform open-source berbasis Linux yang dirancang untuk mengotomatisasi penempatan,                       penskalaan, dan manajemen aplikasi yang berada dalam kontainer.
    b. kubectl: Sebuah baris perintah untuk menjalankan perintah terhadap Kubernetes
    c. pod: Satu grup container instance. Kita bisa menjalankan beberapa container (misalnya aplikasi web          + redis cache + logging service) dalam satu pod. Antar container dalam satu pod bisa saling            mengakses dengan menggunakan alamat localhost.
    d. docker compose: Berfungsi untuk menjalankan container docker secara bersamaan.
    e. docker machine: Tool yang memungkinkan anda menginstall Docker Engine pada virtual hosts, dan                          mengelola hosts dengan command docker-machine.

II. a. Basic Object dari Kobernitas:
        - Pod
        - Service
        - Volume
        - Namespace
    b.  Controller:
        - ReplicaSet
        - Deployment
        - StatefulSet
        - DaemonSet
        - Job
    c. Controller dibangun berdasarkan basic object dan memberikan tambahan fungsionalitas dan fitur          kenyamanan. 

III. kubectl apply -f k8s
     
