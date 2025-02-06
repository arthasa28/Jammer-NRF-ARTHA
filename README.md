<div align="center">

  <img src="https://user-images.githubusercontent.com/62047147/195847997-97553030-3b79-4643-9f2c-1f04bba6b989.png" alt="logo" width="100" height="auto" />
  <h1>nRFBOX</h1>
  
  <p>
    2.4Ghz ULTIMATE Tool
  </p>
  
  
<!-- Badges -->

<a href="https://github.com/cifertech/nrfbox" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=cifertech&message=nrfbox&color=purple&logo=github" alt="arthasa28 - nrfbox"></a>
   
<h4>
    <a href="https://www.instagram.com/artha_sa_/">INSTAGRAM</a>
  <span> · </span>
    <a href="https://arthasa.my.id/">WEBSITE</a>
  </h4>
</div>

<br />


Catatan Rilis nRF-BOX - Versi 2.1.1

Tanggal Rilis: [15/8/2023]

## Fitur Baru

- Penganalisis 128 saluran
- Tampilkan status dengan NeoPixel ws2812

## Peningkatan

- Pengacau 2.4 ditingkatkan dengan kontrol yang lebih baik untuk pemilihan saluran dan memulai serangan
- Pengacau 2.4 lebih efektif (ini memberi Anda opsi untuk menurunkan lalu lintas di saluran tertentu, bukan memutus saluran sepenuhnya)
- Grafik yang lebih sesuai untuk penganalisis saluran

## Perbaikan Bug

- Bug Pemilihan Menu telah diperbaiki
- Bug pemindai RF telah diperbaiki
- Bug pengacau 2.4 telah diperbaiki

===========================================================================




  

<!-- Tentang Proyek -->
## :star2: Tentang Proyek
Dalam proyek ini, saya membuat pemindai/pengacau/Penganalisis Saluran 2,4GHz menggunakan nRF24L01.

<!-- Gambar -->
### :camera: Gambar

<div align="center"> 
  <img src="https://user-images.githubusercontent.com/62047147/206877956-d8b08ef5-fdc4-4f3d-a5c2-49f01483b8cb.jpg" alt="screenshot" />
</div>


<!-- Fitur -->
### :dart: Fitur

- Pindai pita 2,4Ghz
- Pengacau 2,4Ghz
- Penganalisis Saluran

<!-- Memulai -->
## :toolbox: Memulai

Kita akan menggunakan Arduino Pro Mini sebagai prosesor. Selain itu, layar OLED untuk menampilkan Menu dan opsi yang diinginkan. Dengan modul nRF24, kita dapat menjalankan fitur-fiturnya.

- Arduino Pro Mini
- nRF24
- Oled 0,96 SSD1306
<!-- Schematic -->
### :electric_plug: Schematic
Buat koneksi sesuai dengan tabel dan skema di bawah ini.

* Arduino dan nRF24.

| Arduino| nRF24|  
| ----   | -----|
| 9  | CE   |
| 13 | SCK  |
| 12 | MISO |
| 10 | CSN  |
| 11 | MOSI |
| 3V3 | Vcc |
| GND | GND |


* Arduino dan OLED display.

| Arduino| Oled 0.96|
| ----   | -----|
| A5  | SCK |
| A4 | SDA  |
| Vin | VDD |
| GND | GND |

 
* Complete Schematic

<img src="https://user-images.githubusercontent.com/62047147/206878457-5e729716-5ee7-4f6b-97f5-b45559d7cc2a.png" alt="screenshot" width="800" height="auto" />


<!-- Instalasi -->
### :gear: Instalasi

Sebelum mengunggah kode, Anda perlu menginstal pustaka yang diperlukan di Arduino IDE. Ikuti langkah-langkah berikut:

- Ikuti jalur ini Sketch> Include Library> Manage Libraries
- Cari Adafruit SSD1306
- Instal pustaka

-Kemudian cari “GFX” dan instal juga.

-Anda juga memerlukan pustaka "NRF24".

<!-- Penggunaan -->
## :eyes: usage

Setelah mengunggah kode, Menu akan muncul dan Anda dapat memilih opsi yang Anda inginkan.
<img src="https://user-images.githubusercontent.com/62047147/206902220-c793003a-2a08-4eb2-8154-6182c203cf49.jpg" alt="screenshot" width="300" height="auto" />



<!-- License -->
## :warning: License

Didistribusikan di bawah Lisensi MIT. Lihat LICENSE.txt untuk informasi lebih lanjut.
