# web-fondations--24330211027

* 1. Facebook
* ** URL:https://www.facebook.com/
* ** Method:GET
* ** Status code:200 OK
* ** content-Type:text/html

* Request
* Untuk memeriksa atau melihat permintaan pertemanan yang terkirim di Facebook, buka menu Pertemanan Facebook dan lihat permintaan yang Anda kirim.

* Response
* Kesalahan "bad HTTP response code" (kode respons HTTP buruk) di Facebook biasanya berarti perayap (crawler) Facebook tidak dapat mengambil URL situs web Anda dengan benar karena server Anda mengembalikan kode kesalahan seperti 403, 429, atau 500, alih-being kode sukses 200 OK.

*  2. Roblox
* ** URL:https://www.roblox.com
* ** Method:GET
* ** Status code:200 OK
* ** Content-Type:text/html

* Request
* Untuk mengirim permintaan HTTP di Roblox Studio, Anda harus terlebih dahulu mengaktifkan fitur tersebut di pengaturan game Anda dan kemudian menggunakan skrip HttpService milik Lua."

* Response
* Untuk menangani respons HTTP di Roblox,kita menggunakan HttpService untuk mengirim permintaan (requests) dan menguraikan data yang masuk (incoming data).

* 3. Messenger
* ** URL:https://www.messenger.com
* ** Method:GET
* ** status code:200 OK
* ** Content-Type:text/html

* Request
* Di Roblox, melakukan permintaan (request) HTTP ke Messenger (seperti Facebook Messenger atau layanan Webhook/Messenger umum) memerlukan penggunaan HttpService di sisi server.

* Response
* Saat kita mengirim pesan, server messenger (seperti Discord, Telegram, atau Line) akan mengirimkan respons balik untuk memberi tahu apakah pesan tersebut berhasil masuk atau gagal (error).
