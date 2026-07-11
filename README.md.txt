# Akıllı Pediatrik Telemetri Sistemi

Akıllı Pediatrik Telemetri Sistemi, çocuklarda vücut sıcaklığını temassız olarak izlemeyi hedefleyen giyilebilir IoT tabanlı bir prototiptir. Proje; ESP32-C3 mikrodenetleyici, MLX90614 temassız sıcaklık sensörü, SH110X OLED ekran ve Python tabanlı canlı telemetri arayüzünden oluşur.

> Bu proje bir mühendislik prototipidir. Tıbbi tanı, tedavi veya klinik karar amacıyla kullanılmamalıdır.

---

## Özellikler

- Temassız sıcaklık ölçümü
- OLED ekran üzerinden anlık sıcaklık gösterimi
- Kritik sıcaklık seviyesinde görsel uyarı
- Seri port üzerinden bilgisayara veri aktarımı
- Python arayüzü ile canlı grafik izleme
- CSV formatında ölçüm kaydı
- GitHub için sadeleştirilmiş açık kaynak donanım ve yazılım yapısı

---

## Donanım Bileşenleri

| Bileşen | Açıklama |
|---|---|
| ESP32-C3 | Mikrodenetleyici |
| MLX90614 | Temassız sıcaklık sensörü |
| SH110X OLED | Anlık sıcaklık ekranı |
| 2 kademeli On-On anahtar | Cihaz açma/kapama kontrolü |
| Kırmızı LED | Yüksek sıcaklık uyarısı |
| USB kablo | Programlama ve veri aktarımı |

---

## Proje Klasör Yapısı

```text
akilli-pediatrik-telemetri-sistemi/
│
├── README.md
├── LICENSE
│
├── donanim_kodlari/
│   └── telemetri_esp32_c3.ino
│
├── python_arayuz/
│   ├── telemetri.py
│   └── requirements.txt
│
└── gorseller/
    ├── cihaz_kot_pantolon.jpg
    ├── oled_ekran.jpg
    ├── alarm_durumu.jpg
    └── python_arayuz.png