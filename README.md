# Wemos D1 Mini ile OLED Saat ve WiFi Sinyal Gücü Göstergesi

Bu proje, ESP8266 mikrodenetleyici, OLED ekran ve NTPClient kütüphanesini kullanarak zamanı, tarihi ve WiFi sinyal gücünü gösteren bir saat oluşturur. OLED ekran, önceden belirlenmiş saatlere dayanarak gün ve gece modları arasında değişir.

# Özellikler;

NTP kullanarak gerçek zamanlı saat senkronizasyonu
Zaman bazlı dinamik ekran modu (gün/gece)
WiFi sinyal gücü göstergesi
Basit ve kullanımı kolay
Donanım Gereksinimleri
ESP8266 mikrodenetleyici
OLED ekran (SSD1306)
WiFi bağlantısı

# Kullanılan Kütüphaneler;

Adafruit GFX Kütüphanesi
Adafruit SSD1306 Kütüphanesi
ESP8266WiFi Kütüphanesi
NTPClient Kütüphanesi
WiFiUdp Kütüphanesi

# Kurulum;

Arduino IDE'yi açın.
Gerekli kütüphaneleri yükleyin (Adafruit GFX, Adafruit SSD1306, ESP8266WiFi, NTPClient, WiFiUdp).
ESP8266 geliştirmesi için Arduino IDE'nizi ayarlayın.
ESP8266_OLED_Saat.ino dosyasını açın.
WiFi kimlik bilgilerinizi kod içinde yapılandırın.
Kodu ESP8266 cihazınıza yükleyin.

# Kullanım;

ESP8266'yı güce bağlayın.
Saat WiFi'ye bağlanacak ve NTP ile senkronize olacaktır.
OLED ekran, mevcut saati, tarihi ve WiFi sinyal gücünü gösterecektir.
Gün ve gece modu, önceden belirlenmiş saatlere göre değişecektir.

# Sorun Giderme;

WiFi bağlantısı ile ilgili sorunlarla karşılaşırsanız, kimlik bilgilerinizi kod içinde kontrol edin.
Donanım bağlantılarının doğru olduğundan emin olun.
Başka sorunlar için Sorunlar bölümüne veya yeni bir sorun oluşturun.
