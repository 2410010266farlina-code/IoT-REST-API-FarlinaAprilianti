
# IoT REST API - Farlina Aprilianti

## Deskripsi Proyek
Proyek ini merupakan implementasi Internet of Things (IoT) untuk memantau data suhu dan kelembapan sensor menggunakan Node-RED, MQTT, dan REST API. Data sensor ditampilkan melalui dashboard berbasis web secara real-time.

## Teknologi yang Digunakan
- Node-RED
- MQTT (Mosquitto)
- Python
- HTML, CSS, dan JavaScript
- Chart.js
- WebSocket
- SQLite

## Fitur Utama
1. Monitoring suhu dan kelembapan sensor.
2. REST API untuk mengambil data sensor.
3. Kontrol perangkat melalui API.
4. Penyimpanan riwayat data sensor.

## Pengembangan Tambahan
1. **Endpoint PUT /api/threshold** untuk mengatur batas suhu dan memberikan notifikasi ketika suhu melewati batas.
2. **Grafik real-time Chart.js** untuk menampilkan perubahan suhu.
3. **Autentikasi API Key** menggunakan header `X-API-Key`.
4. **WebSocket** untuk pembaruan data sensor secara real-time tanpa polling.
5. **Database SQLite** untuk menyimpan dan mengambil riwayat data sensor.

## Struktur File
- `dashboard.html` - Tampilan dashboard monitoring.
- `simulasi_esp32.py` - Simulasi pengiriman data sensor.
- `flows.json` - Flow Node-RED hasil ekspor.
- `iot_history.db` - Database riwayat sensor (jika disertakan).

## Cara Menjalankan
1. Jalankan Mosquitto Broker.
2. Jalankan Node-RED.
3. Import file flow JSON ke Node-RED.
4. Jalankan program simulasi sensor Python.
5. Buka dashboard melalui `http://localhost:1880/dashboard.html`.

## Pengembang
**Farlina Aprilianti**

Proyek IoT REST API.
