# Intent
Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum intent dalam aplikasi Android yaitu :
- Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
- Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.
# constraint layout
ConstraintLayout merupakan salah satu komponen ViewGroup yang dapat kita gunakan untuk menyusun tampilan aplikasi yang kompleks tanpa adanya nested layout.
# Intent di bagi menjadi 2 :
- Intent Explicit yang berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
- Intent Implisit yang berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti : Dial Number, dan lainnya.

![Intent1](https://user-images.githubusercontent.com/63888291/107380730-b7b2b580-6b20-11eb-8088-dc15565c91c7.jpeg)
![Intent2](https://user-images.githubusercontent.com/63888291/107380736-ba150f80-6b20-11eb-808d-526ef9b0aae9.jpeg)
