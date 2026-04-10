# 🚀 GitCan Desktop

<p align="center">
  <img src="./bangit.svg" width="100%" alt="GitCan Banner" />
</p>

<p align="center">
  <b>Modern, hızlı ve geliştirici dostu GitHub masaüstü yöneticisi</b>
</p>

<p align="center">
  GitHub repolarını görsel, sade ve güçlü bir masaüstü deneyimiyle yönetmek için geliştirildi.
</p>

---

## 🧠 Overview

**GitCan Desktop**, GitHub ile etkileşimi tamamen görselleştiren modern bir masaüstü uygulamasıdır.  
Tauri + React mimarisiyle geliştirilmiş olup performans, sadelik ve gerçek kullanım senaryoları odağa alınmıştır.

CLI kullanımını minimuma indirir ve kullanıcıya tek bir arayüz üzerinden:

- Repository oluşturma
- Repository listeleme
- Repository güncelleme ve silme
- Dosya ve klasör yükleme
- Repository içeriğini görüntüleme
- GitHub hesabı ile güvenli giriş

deneyimi sunar.

---

## ⚡ Core Features

### 🔐 GitHub Authentication
- GitHub Device Flow ile giriş
- Güvenli token yönetimi
- Yerel oturum saklama
- Hızlı ve sade kimlik doğrulama akışı

### 📦 Repository Management
- Public / Private repository oluşturma
- Kullanıcı repolarını listeleme
- Repository bilgilerini güncelleme
- Repository silme işlemleri
- Varsayılan branch bilgisini yönetme

### 📁 File & Folder Operations
- Bilgisayardan dosya veya klasör seçme
- Recursive klasör kopyalama
- Boş klasörler için otomatik `.gitkeep` oluşturma
- Güvenli fallback kopyalama sistemi

### 📂 Explorer Experience
- Repository içeriğini görüntüleme
- Klasörler arasında gezinme
- Dosya önizleme desteği
- Text ve HTML içeriklerini inceleme
- Modal tabanlı modern explorer yapısı

### 🚀 Upload & Progress Tracking
- Adım adım ilerleme takibi
- Gerçek zamanlı progress bilgisi
- Yüzdelik durum göstergesi
- Log tabanlı işlem akışı
- Hata durumlarını kullanıcıya gösterme

### 🖥️ Native Desktop Experience
- Tauri tabanlı hafif ve hızlı yapı
- Native pencere kontrolü
- Sistem dialog entegrasyonu
- Yerel dosya sistemi ile güçlü etkileşim

### 🎨 Modern UI / UX
- Koyu tema odaklı modern tasarım
- Minimal ve temiz arayüz
- Splash screen deneyimi
- Özel alert sistemi
- Geliştirici dostu akışlar

---

## 🧩 Architecture

### Frontend
- React
- Vite
- TypeScript
- Component-based UI yapısı
- Event-driven kullanıcı akışı

### Backend
- Rust
- Tauri
- Async işlemler
- Native file system operasyonları
- GitHub API ile güçlü entegrasyon

### Communication Layer
- Frontend ve backend arasında `invoke()` tabanlı haberleşme
- Event emitter ile canlı işlem durumu aktarımı
- Native ve web katmanı arasında temiz köprü yapısı

---

## 🔐 Security & Permissions

GitCan Desktop, masaüstü uygulamalar için daha kontrollü ve güvenli bir yaklaşım benimser.

- Capability tabanlı izin yapısı
- Store erişim yönetimi
- Shell yetkileri
- Dialog izinleri
- Window kontrolleri için tanımlı permission sistemi

Bu yapı sayesinde uygulama hem güçlü masaüstü yetenekleri sunar hem de erişimleri kontrollü tutar.

---

## 🎯 Design Philosophy

GitCan şu temel prensiplerle geliştirildi:

- **Zero friction UX**  
  Kullanıcı mümkün olduğunca az teknik bariyerle işlem yapabilmeli.

- **Native performance**  
  Hafif, hızlı ve masaüstüne uygun bir deneyim sunulmalı.

- **Visual-first Git workflow**  
  Komut satırı zorunluluğu olmadan GitHub işlemleri yapılabilmeli.

- **Modular structure**  
  Uygulama gelecekte yeni özelliklerle kolayca genişletilebilmeli.

---

## 🔥 Highlights

- Tauri + React hibrit mimari
- GitHub Device Flow entegrasyonu
- Repository yönetimi için sade masaüstü deneyimi
- Dosya ve klasör bazlı içerik yükleme akışı
- Gerçek zamanlı progress sistemi
- Explorer ve preview tabanlı içerik görüntüleme
- Modern koyu tema arayüzü

---

## 🚧 Roadmap

- [ ] Branch management
- [ ] Commit / Push control
- [ ] Drag & Drop upload
- [ ] Multi-account support
- [ ] Diff viewer
- [ ] Offline cache support

---

## 👨‍💻 Developer

**Serhat Can**  
📍 Samsun, Türkiye  
🔗 GitHub: [serhatcan44](https://github.com/serhatcan44)

---

## ⭐ Support

Projeyi beğendiysen repo'ya yıldız vermeyi unutma.

GitCan Desktop aktif olarak geliştirilmektedir.
