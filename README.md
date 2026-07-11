# Akıllı Pediatrik Telemetri Sistemi

Çocuklarda vücut sıcaklığının sürekli ve otonom bir şekilde takip edilmesini sağlayan, ESP32-C3 ve Python tabanlı akıllı telemetri sistemi arayüzü (Prototip).

## 🚀 Proje Hakkında

Bu proje, pediatrik hastaların vücut sıcaklığı gibi hayati verilerini uzaktan, kablosuz ve gerçek zamanlı olarak izlemek amacıyla geliştirilmiştir. Giyilebilir sağlık teknolojileri ve akıllı tekstil (smart denim) konseptlerine uygun olarak tasarlanan sistem, verimli bağlantı ve düşük güç tüketimi için **ESP32-C3** mikrodenetleyicisi kullanmaktadır. Elde edilen veriler, **Python** tabanlı bir arayüz üzerinden işlenmekte ve takip edilmektedir.

## 🛠️ Donanım ve Yazılım Özellikleri

### Donanım (Hardware)
* **Mikrodenetleyici:** ESP32-C3 (Gelişmiş bağlantı ve düşük güç tüketimi)
* **Sensörler:** Hassas termal sıcaklık sensörleri
* **Devre Elemanları:** 2 kademeli (On-On) sürgülü switch ve güç modülleri

### Yazılım (Software)
* **Gömülü Sistem:** C/C++ (ESP32 veri okuma ve kablosuz aktarım)
* **Arayüz ve Veri İşleme:** Python 
* **Haberleşme Protokolü:** Wi-Fi / Bluetooth LE (Telemetri veri aktarımı)

## ⚙️ Kurulum ve Kullanım

### Gereksinimler
* Python 3.x
* Gerekli Python kütüphaneleri (örneğin: `pyserial`, arayüz kütüphaneleri vb.)
* Arduino IDE veya PlatformIO (ESP32-C3 kodlarını yüklemek için)

### Adımlar
1. Bu depoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/emir-dogu/akilli-pediatrik-telemetri.git](https://github.com/emir-dogu/akilli-pediatrik-telemetri.git)
