<details>
<summary>Tutorial 8</summary>

a. How many data your publlsher program will send to the message broker in one
run?

Jawab : Program penerbit (publisher) Anda akan mengirimkan sejumlah data ke broker pesan dalam satu jalankanannya tergantung pada panggilan yang terjadi pada "publish_event". Pada kali ini, terjadi lima panggilan kepada "publish_event" jadi data yang dikirim ke broker ada lima tiap kali jalan.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

Jawab : Jika URL "amqp://guest:guest@localhost:5672" digunakan baik dalam program pelanggan (subscriber) maupun program penerbit (publisher), itu berarti keduanya akan terhubung ke broker pesan yang sama dengan konfigurasi yang sama juga. Dengan kata lain, mereka akan berkomunikasi melalui protokol AMQP dengan menggunakan kredensial yang sama untuk otentikasi, dan broker pesan akan berada pada mesin lokal Anda (localhost) di port default AMQP (5672). Ini memungkinkan kedua program untuk berinteraksi dengan pesan yang sama yang dipublikasikan melalui broker pesan yang sama.

<a href="https://ibb.co/bz6VH3J"><img src="https://i.ibb.co/9sp0wvt/Rabbit-MQ-1.png" alt="Rabbit-MQ-1" border="0"></a>

</details>