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

![image](https://user-images.githubusercontent.com/60589670/107396475-5db9ec00-6b30-11eb-829d-598abbdfa55f.png)
![image](https://user-images.githubusercontent.com/60589670/107396602-7e824180-6b30-11eb-83bf-ed43b080bd13.png)
