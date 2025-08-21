# All-in Cajon "Pokorinta"

![Pokorinta](pokorinta.png)

## English

### Overview
This repository contains the program for All-in Cajon "Pokorinta" exhibited at NT Kyoto 2025.

**All-in Cajon "Pokorinta" is an automatic rhythm machine shaped like a cajon.**  
Inside the box are instruments such as tambourines and cymbals. Despite its compact body, it can produce a variety of sounds like a drum set. Seven electronically controlled solenoids rhythmically strike these instruments to create pleasant rhythms. Both the instruments and the control system are integrated into a single enclosure, which is why it is called "All-in Cajon."

**Features:**
- Pressing the button on the main unit starts the performance.
- Performance data uses MIDI files stored on an SD card. The data from drum channel (9) is read, and each drum instrument is mapped to Pokorinta's solenoids for playback.

**Demo Video:**  
[Playing 'Senbonzakura' on Pokorinta Cajon @NT Kyoto 2025](https://youtu.be/M3PQvyEZkvs?si=6jQbiOPsckav4VGM)

**Circuit diagram:**  
[pokorinta_circuit.pdf](pokorinta_circuit.pdf)
- Microcontroller board: M5Stamp S3

**X Account:**  
[Pokorinta Laboratory](https://x.com/tobu_8_kaeru)

### Development Environment
- IDE: Arduino IDE
- Board: M5Stack by M5Stack official v.2.1.3
- Libraries:
  - Adafruit BusIO by Adafruit v.1.17.0
  - RTClib by Adafruit v.2.1.4
  - SdFat by Bill Greiman v.2.3.0

---

## 日本語

### 概要
本リポジトリは、NT京都2025で展示した All-in Cajon "Pokorinta" のプログラムを格納しています。

**All-in Cajon "Pokorinta" はカホンの見た目をした自動演奏リズムマシンです。** 箱の内部にはタンバリンやシンバルなどの楽器が入っており、コンパクトな筐体でありながら、ドラムセットのような多様な音を奏でることができるのが特徴です。また、それらを電子制御された7個のソレノイドでリズミカルに叩くことによって、心地よいリズムを奏でます。楽器も制御も一つの筐体に集約されているところから、All-in Cajonと名付けました。

**機能:**
- 本体のボタンを押すことで演奏が開始されます。
- 演奏データはSDカードに保存されたMIDIファイルを使用します。ドラムチャネル(9)のデータを読み込み、ドラムの各楽器をPokorintaのソレノイドにマッピングし、演奏を行います。

**デモ動画:**  
[自動演奏カホン「Pokorinta」で『千本桜』を叩いてみた！@NT京都2025](https://youtu.be/M3PQvyEZkvs?si=6jQbiOPsckav4VGM)

**回路図:**  
[pokorinta_circuit.pdf](pokorinta_circuit.pdf)
- マイコンボード：M5Stamp S3

**Xアカウント:**  
[Pokorinta Laboratory](https://x.com/tobu_8_kaeru)

### 開発環境
- IDE: Arduino IDE
- Board: M5Stack by M5Stack official v.2.1.3
- Libraries:
  - Adafruit BusIO by Adafruit v.1.17.0
  - RTClib by Adafruit v.2.1.4
  - SdFat by Bill Greiman v.2.3.0
