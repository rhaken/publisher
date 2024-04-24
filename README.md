
# Tutorial 8 - Publisher - Refleksi

## a) How many data your publisher program will send to the message broker in one run?
Program publisher akan mengirimkan 5 pesan data ke pialang pesan dalam satu kali jalankan. Hal ini karena ada 5 panggilan metode `publish_event`, masing-masing memublikasikan sebuah instance `UserCreatedEventMessage`.

## b) The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
URL "amqp://guest:guest@localhost:5672" sama di kedua program publisher dan subscriber, yang berarti keduanya terhubung ke instance pialang pesan yang sama yang berjalan di localhost dengan port 5672.

Ini berarti bahwa publisher dan subscriber sedang berkomunikasi melalui pialang pesan yang sama, memungkinkan mereka untuk bertukar pesan dengan lancar.

# RunningRabbitMQ
![image](https://github.com/rhaken/publisher/assets/39646450/831313f1-f780-4380-ba3c-44817e09603c)

# RunningRabbitMQ
![image](https://github.com/rhaken/publisher/assets/39646450/cbf617c4-74f3-4369-9b39-35d3bfcf795b)

# MessageQueeProcessing
![image](https://github.com/rhaken/publisher/assets/39646450/7d0c2ba3-8dc4-4af5-b898-1081ae20945d)



