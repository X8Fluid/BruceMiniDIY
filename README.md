# Bruce Mini DIY - X8Fluid 🚀

Selamlar! İlk DIY projem olan **Bruce Mini DIY** projesi; NodeMCU-ESP32, ESP32-WROOM ve ESP32-U (TAVSİYE EDİLİR) gibi modellerde çalışabilir. Ekran olarak 1.14 inç ST7789V2 kullanılmıştır. Donanıma NRF24, PN532 ve CC1101 modülleri takılabilir. Bruce yazılımında bulunan tüm özellikler bu DIY projesinde yer almaktadır.

Cihazınızı sorunsuz bir şekilde yapabilmeniz ve çalıştırabilmeniz için ihtiyacınız olan tüm donanım, pin şeması ve dosyaları bu repoda bulabilirsiniz.

---

## 🔌 ESP32 WROOM Pin Şeması

<blockquote>
  <strong>🎛️ Butonlar:</strong><br>
  • OK PIN: 5<br>
  • YUKARI (UP) PIN: 15<br>
  • AŞAĞI (DOWN) PIN: 14
</blockquote>

<blockquote>
  <strong>📺 Ekran (1.14 inç 135x240 ST7789V2):</strong><br>
  • TFT_CS = 13<br>
  • TFT_DC = 2<br>
  • TFT_RST = 4<br>
  • TFT_MOSI = 23<br>
  • TFT_SCLK = 18<br>
  • TFT_BL = 22
</blockquote>

<blockquote>
  <strong>🔄 Varsayılan I2C Pinleri:</strong><br>
  • SDA: 21<br>
  • SCL: 22
</blockquote>

<blockquote>
  <strong>📡 SPI Pinleri:</strong><br>
  • SCK_PIN = 32<br>
  • MOSI_PIN = 27<br>
  • MISO_PIN = 12<br>
  • SS_PIN = 33
</blockquote>

---

## 🚀 Kurulum ve Çalıştırma

Yüklediğim `bin files` klasöründeki firmware dosyasını ESP32 aracınızla flaşlayarak direkt kullanmaya başlayabilirsiniz. 
Flaşlama ayarını(0x0 yapıp o şekilde flaşlamanız gerekiyor.)

---

## 📷 Cihaz Görselleri ve Bağlantı Şeması

### 🛠️ Geliştirilen Donanım
Aşağıda, montajı tamamlanmış ve stabil çalışan Bruce Mini DIY cihazına ait görsel yer almaktadır:

![Bruce Mini DIY](photos/Brucefoto.jpeg)

### 📚 Devre Şeması
Aşağıdaki basit devre şemasını takip ederek Bruce yazılımını cihazınızda stabil bir şekilde çalıştırabilirsiniz:

![Devre Şeması](photos/Bruce%20DIY%20Github.png)