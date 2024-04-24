
# Tutorial 8 - Publisher - Refleksi

## a) How many data your publisher program will send to the message broker in one run?
Program publisher akan mengirimkan 5 pesan data ke pialang pesan dalam satu kali jalankan. Hal ini karena ada 5 panggilan metode `publish_event`, masing-masing memublikasikan sebuah instance `UserCreatedEventMessage`.

## b) The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
URL "amqp://guest:guest@localhost:5672" sama di kedua program publisher dan subscriber, yang berarti keduanya terhubung ke instance pialang pesan yang sama yang berjalan di localhost dengan port 5672.

Ini berarti bahwa publisher dan subscriber sedang berkomunikasi melalui pialang pesan yang sama, memungkinkan mereka untuk bertukar pesan dengan lancar.
