# 🎄 3D Interactive Christmas Tree

Bu proje, **"Bu sene yılbaşı ağacı süslemek yerine kodluyorum"** akımından ilham alınarak, modern web teknolojileri ve 3D grafik kütüphaneleri kullanılarak geliştirilmiştir.

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Proje+Ekran+Goruntusu+Buraya" alt="Yılbaşı Ağacı Demo" width="100%">
  </p>

## 🔗 Canlı Demo (Live Demo)
Projeyi canlı görüntülemek için: **[BURAYA TIKLAYIN]([https://selcukzeynep.github.io/threejs-3d-christmas-tree/])**


## 🚀 Proje Hakkında
Bu çalışma, standart HTML/CSS sınırlarını aşarak, tarayıcı üzerinde gerçek zamanlı 3D render işlemi gerçekleştirmektedir. Kullanıcılar ağacı mouse veya dokunmatik kontrollerle 360 derece inceleyebilir, yakınlaşıp uzaklaşabilirler.

Amaç, kış atmosferini ve yılbaşı ruhunu dijital bir deneyime dönüştürmektir.

## ✨ Özellikler

* **Gerçekçi 3D Modelleme:** Basit geometrik şekiller yerine, yüzlerce parçadan oluşan detaylı ağaç yapısı.
* **Yüksek Performans (InstancedMesh):** 8000'den fazla yaprak ve yüzlerce süs, `Three.js InstancedMesh` teknolojisi ile tek bir "draw call" içinde çizdirilerek maksimum FPS (kare hızı) sağlanmıştır.
* **Dinamik Işıklandırma & Gölgeler:** Sahneye derinlik katan ortam ışığı (Ambient), spot ışıklar ve gerçek zamanlı gölge hesaplamaları.
* **Partikül Sistemi (Particle System):** Derinlik algısına sahip, sürekli döngüde çalışan kar yağışı efekti.
* **İnteraktif Kontroller:** `OrbitControls` sayesinde tam kamera kontrolü.
* **Responsive Tasarım:** Mobil ve masaüstü cihazlara otomatik uyum sağlayan dinamik kanvas yapısı.

## 🛠️ Kullanılan Teknolojiler

* **JavaScript (ES6+)**
* **Three.js** (3D Grafik Motoru)
* **HTML5 & CSS3**
* **Vite / Webpack** (Modül yükleme yapısı - CDN üzerinden)

## 💻 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için:

1.  Bu repoyu klonlayın:
    ```bash
    git clone [https://github.com/kullaniciadi/yilbasi-agaci.git](https://github.com/kullaniciadi/yilbasi-agaci.git)
    ```
2.  Klasörün içine girin ve `index.html` dosyasını bir "Live Server" eklentisi ile veya yerel sunucu ile açın.
    *(Three.js güvenlik politikaları gereği doğrudan dosya açıldığında dokular yüklenmeyebilir, yerel sunucu önerilir.)*

## 📝 Özelleştirme

`index.html` dosyası içerisindeki parametreleri değiştirerek ağacı kişiselleştirebilirsiniz:

* `leafCount`: Ağacın yoğunluğunu artırır/azaltır.
* `ornamentCount`: Süs sayısını belirler.
* `colors`: Materyal renklerini (Hex kodu ile) değiştirebilirsiniz.

---

<p align="center">
  Mutlu Yıllar! 🎁🎅
</p># threejs-3d-christmas-tree
