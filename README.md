# Multi-Detection: Yüz, Göz ve Gülümseme Algılama

Bu proje, OpenCV kütüphanesini kullanarak yüz, göz ve gülümseme algılama işlemlerini gerçekleştirir. Webcam üzerinden alınan görüntülerde bu öğeleri tespit eder, algıladığında etraflarına dikdörtgenler çizer ve sonuçları ekranda gösterir.

## Gereksinimler

Projenin çalışabilmesi için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:

- `opencv-python` (görüntü işleme ve yüz tespiti için)

Gerekli kütüphaneyi yüklemek için aşağıdaki komutu çalıştırabilirsiniz:

```bash
pip install opencv-python

proje_dizini/
│
├── multi_detection.py       # Yüz, göz ve gülümseme algılama işlemleri
├── classifier/              # Haarcascade dosyalarının bulunduğu klasör
│   ├── haarcascade_frontalface_default.xml
│   ├── haarcascade_eye.xml
│   └── haarcascade_smile.xml
