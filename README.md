# Module 10: Asynchronous Programming (Broadcast) Reflection

## Experiment 2.1: Original code, and how it run

Program dijalankan dengan membuka satu terminal untuk server memakai cargo run --bin server, lalu beberapa terminal lain untuk client memakai cargo run --bin client. Setelah server aktif, setiap client bisa mengetik pesan dari terminalnya masing-masing, lalu pesan itu dikirim ke server dan diteruskan ke client lain yang sedang terhubung. Dari percobaan ini terlihat kalau server berfungsi sebagai penghubung broadcast, jadi pesan yang dikirim dari satu client bisa langsung muncul di client lain secara real-time.