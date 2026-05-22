# Kişisel Web Sayfası ve Docker Projesi

### Proje Bilgileri
- **Öğrenci Adı:** Havva Taşkaya
- **Kullanılan Teknolojiler:** HTML5, CSS3, Docker, Nginx

### Proje Açıklaması
Bu proje, Bulut Bilişim dersi kapsamında Docker container mimarisi kullanılarak Nginx web sunucusu üzerinde ayağa kaldırılan basit bir kişisel tanıtım web sayfasıdır.

### Docker Çalıştırma Komutları
Proje klasörünün içinde terminali açarak sırasıyla şu komutları çalıştırabilirsiniz:

1. **Docker Image Oluşturma:**
   

   docker build -t webproje .
2. **Docker container çalıştırma:**
   docker run -d -p 8080:80 webproje

   