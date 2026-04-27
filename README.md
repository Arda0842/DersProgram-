<img width="1919" height="905" alt="image" src="https://github.com/user-attachments/assets/fc674eb4-291f-4da6-8f6b-2c8038a389ae" />


# 🗓️ Pratik Ders Programı Oluşturucu

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Okullarda ders programı hazırlamak için kullanılan eski, hantal ve kurulum gerektiren masaüstü yazılımlara modern, hızlı ve tamamen web tabanlı bir alternatif. 

Hiçbir uygulama indirmenize, üye olmanıza veya sunucu kurmanıza gerek kalmadan; doğrudan tarayıcınız üzerinden öğretmenlerinizi ekleyebilir, ders atamalarını yapabilir, tek tıkla otomatik program oluşturup PDF olarak indirebilirsiniz.

## ✨ Öne Çıkan Özellikler

* **🚀 Kurulumsuz & Hızlı:** Tamamen istemci tarafında (client-side) çalışır. İndirme veya kurulum gerektirmez.
* **🤖 Otomatik Yerleştirme Algoritması:** Girilen ders atamalarını ve öğretmenlerin "müsait olmadığı" saatleri (blokları) dikkate alarak ders programını saniyeler içinde otomatik oluşturur.
* **⚠️ Çakışma Kontrolü:** Manuel düzenlemelerde aynı öğretmenin aynı saatte iki farklı sınıfa atanmasını engelleyen akıllı uyarı sistemi.
* **💾 Otomatik Kayıt (Local Storage):** Girdiğiniz tüm öğretmen, sınıf ve program verileri tarayıcınızda güvenle saklanır. Sayfayı kapatsanız bile verileriniz kaybolmaz.
* **📄 Anında PDF Çıktısı:** Hazırlanan ders programını `jsPDF` kütüphanesi entegrasyonu ile saniyeler içinde, A4 boyutunda, renk kodlu ve profesyonel bir PDF tablosu olarak cihazınıza indirir.
* **📋 Çift Görünüm Modu:** Programı hem "Sınıf" bazlı hem de "Öğretmen" bazlı inceleme ve düzenleme imkanı.

## 🛠️ Kullanılan Teknolojiler

Proje, dış bağımlılıkları en aza indirmek ve en yüksek performansı sağlamak amacıyla saf (vanilla) web teknolojileri ile geliştirilmiştir:

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid mimarisi)
* **Mantık & Algoritma:** Vanilla JavaScript (ES5/ES6)
* **PDF Dışa Aktarım:** `jsPDF` Kütüphanesi (CDN üzerinden)
* **Veri Saklama:** Tarayıcı `localStorage` API

## 📂 Dosya Yapısı

Proje tamamen taşınabilir ve tek dosyadan oluşmaktadır:

```text
├── index.html        # Uygulamanın tüm arayüzü, CSS stilleri ve JS algoritmalarını barındıran ana dosya
└── README.md         # Proje dokümantasyonu
