# Intent
Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar
komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum
intent dalam aplikasi Android yaitu:
- Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- Menjalankan background service, misalnya melakukan sinkronisasi ke server dan
menjalankan proses berulang (periodic/scheduler task).
- Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi
membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai
melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh
sistem Android untuk event booting tersebut.

Intent memiliki dua bentuk yaitu:
1.	Explicit Intent 
Adalah tipe Intent yang digunakan untuk menjalankan komponen dari dalam sebuah aplikasi. Explicit intent bekerja dengan menggunakan nama kelas yang dituju misal : com.dicoding.activity.DetailActivity. Umumnya intent ini digunakan untuk mengaktifkan komponen pada satu aplikasi.
2.	Implicit Intent 
Adalah tipe intent yang tidak memerlukan detail nama kelas yang ingin diaktifkan. Model ini memungkinkan komponen dari aplikasi lain bisa merespon request intent yang dijalankan.
Penggunaan tipe intent ini umumnya diperuntukkan untuk menjalankan fitur/fungsi dari komponen aplikasi lain. Contohnya ketika kita membutuhkan fitur untuk mengambil foto. Daripada membuat sendiri fungsi kamera, lebih baik kita menyerahkan proses tersebut pada aplikasi kamera bawaan dari peranti atau aplikasi kamera lain yang telah terinstal sebelumnya di peranti.
Hal yang sama misalnya ketika kita membutuhkan fungsi berbagi konten. Kita bisa memanfaatkan intent untuk menampilkan aplikasi mana saja yang bisa menangani fitur tersebut.
Implementasi implicit intent ini akan sangat memudahkan bagi pengembang agar tetap fokus pada proses bisnis inti dari aplikasi yang dikembangkan.


![image](https://user-images.githubusercontent.com/60589670/107396475-5db9ec00-6b30-11eb-829d-598abbdfa55f.png)
![image](https://user-images.githubusercontent.com/60589670/107396602-7e824180-6b30-11eb-83bf-ed43b080bd13.png)
