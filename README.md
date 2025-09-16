# Automatic-Water-Pump-System-with-Ultrasonic-Sensor-and-LCD
# 💧 Automatic Water Pump Controller with Ultrasonic Sensor and LCD

Proyek ini adalah **sistem pengendali pompa air otomatis** berbasis **ESP32/Arduino**.  
Sistem menggunakan **sensor ultrasonik HC-SR04** untuk mengukur ketinggian air dalam tandon, dan menampilkan informasi jarak serta status pompa di **LCD I2C 16x2**.  
Pompa dikontrol melalui **relay** yang menyala/mati otomatis sesuai level air.

🔗 **Live Simulation on Wokwi**  
👉 [Klik di sini untuk membuka proyek di Wokwi](https://wokwi.com/projects/417231761290364929)

---

## 🚀 Fitur Proyek
- Mengukur ketinggian air dengan **HC-SR04 Ultrasonic Sensor**.  
- Menampilkan jarak air (cm) di **LCD I2C**.  
- Menghidupkan pompa saat air hampir habis (≤ 10 cm dari dasar).  
- Mematikan pompa saat tandon hampir penuh (≤ 10 cm dari permukaan).  
- Sistem bekerja otomatis tanpa intervensi manual.

---

## 🛠️ Hardware
- ESP32 / Arduino Uno / Nano  
- Ultrasonic Sensor **HC-SR04**  
- LCD I2C 16x2  
- Relay Module  
- Pompa Air (real atau simulasi di Wokwi)  

---

