# 🔧 Otomotik - Araba Parçaları Ansiklopedisi

Web Tasarım dersi kapsamında geliştirilmiş, **Public API** kullanarak veri çekme, listeleme, ekleme, silme ve güncelleme işlemlerini içeren bir CRUD uygulamasıdır.

## 🚀 Özellikler

### Zorunlu Özellikler
- ✅ Veri listeleme
- ✅ Veri ekleme
- ✅ Veri silme
- ✅ Veri güncelleme
- ✅ fetch API
- ✅ async / await
- ✅ DOM Manipülasyonu
- ✅ Event Listener
- ✅ Responsive tasarım

### ⭐ Ekstra Özellikler
- 🔍 Arama sistemi
- 🏷️ Kategori filtreleme (Motor, Yakıt, Turbo, Elektrik, Şanzıman, Fren, Egzoz)
- 🌙 Dark Mode (LocalStorage ile kalıcı)
- 💾 LocalStorage
- ⏳ Loading animasyonu
- 🔔 Toast mesajları
- 📊 İstatistik kartları

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|-----------|----------|
| HTML5 | Yapı iskeleti |
| CSS3 | Stil ve responsive tasarım |
| JavaScript | Tüm işlevsellik |
| DummyJSON API | Fake API veri kaynağı |
| LocalStorage | Kullanıcı verilerini saklama |

## 📦 API Kullanımı

Proje **DummyJSON** fake API'sini kullanmaktadır.

| İşlem | Metod | Endpoint |
|-------|-------|----------|
| Listeleme | GET | `https://dummyjson.com/posts` |
| Ekleme | POST | `https://dummyjson.com/posts/add` |
| Güncelleme | PUT | `https://dummyjson.com/posts/:id` |
| Silme | DELETE | `https://dummyjson.com/posts/:id` |

## 💻 Kurulum

1. Projeyi indirin veya kodu kopyalayın
2. `index.html` dosyasını bir web tarayıcısında açın
3. Veya VS Code ile açıp **Live Server** ile çalıştırın

## 🎯 Kullanım

| İşlem | Nasıl Yapılır |
|-------|---------------|
| Parça Ekleme | Formu doldurup "Kaydet" butonuna tıklayın |
| Parça Düzenleme | Karttaki "Düzenle" butonuna tıklayıp güncelleyin |
| Parça Silme | Karttaki "Sil" butonuna tıklayıp onaylayın |
| Arama Yapma | Arama kutusuna kelime yazın |
| Kategori Filtreleme | Kategori butonlarına tıklayın |
| Dark Mode | Sağ üstteki butona tıklayın |


## 🔄 CRUD İşlemleri

| İşlem | Açıklama |
|-------|----------|
| CREATE (Ekle) | Yeni araba parçası ekler |
| READ (Listele) | API'den verileri çeker ve listeler |
| UPDATE (Güncelle) | Mevcut parçayı düzenler |
| DELETE (Sil) | Parçayı listeden kaldırır |

## 🌟 Notlar

- Proje tamamen Türkçe arayüze sahiptir
- API'den gelen veriler sadece araba parçaları filtrelenerek gösterilir
- Kullanıcı eklemeleri LocalStorage'da saklanır, sayfa kapatılsa bile kaybolmaz
- Tüm cihazlara uyumlu responsive tasarım

## 👨‍💻 Ders Bilgisi

**Ders:** Web Tasarımı  
**Konu:** JavaScript ile Public API Kullanımı ve CRUD İşlemleri

---

© 2024 Otomotik Projesi

## 📁 Proje Yapısı
