# Tubes Cursor Effect

3D tüp animasyonları ile interaktif cursor efekti.

## Nasıl Çalıştırılır

### ⚡ Kolay Yöntem: Tek Tıkla Aç

Modern tarayıcılarda (Chrome 89+, Firefox 108+, Safari 16.4+) `index.html` dosyasına çift tıklayın veya dosyayı tarayıcıya sürükleyin.

**Not:** Eğer beyaz sayfa görüyorsanız, aşağıdaki HTTP server yöntemini kullanın.

### 🚀 Önerilen: HTTP Server ile Aç

**Windows:**
- `start-server.bat` dosyasına çift tıklayın
- Tarayıcınızda `http://localhost:8000` adresine gidin

**Mac/Linux:**
```bash
chmod +x start-server.sh
./start-server.sh
```
Sonra tarayıcınızda `http://localhost:8000` adresine gidin

### 🔧 Manuel Başlatma

```bash
python3 -m http.server 8000
```

Tarayıcınızda `http://localhost:8000` adresine gidin

## Özellikler

- ✨ 3D tüp animasyonları
- 🎨 Başlangıç renkleri: `#f967fb`, `#53bc28`, `#6958d5`
- 💡 Işık renkleri: `#83f36e`, `#fe8a2e`, `#ff008a`, `#60aed5`
- 🖱️ Herhangi bir yere tıklayarak rastgele renk değiştirme
- 📱 Mobil uyumlu (touch-action: none)

## Kullanılan Teknolojiler

- [Three.js](https://threejs.org/) - 3D grafik kütüphanesi
- [threejs-components](https://www.npmjs.com/package/threejs-components) - Hazır Three.js bileşenleri
