🚀 GitCan Desktop
<p align="center"> <img src="./banner_gitcan_final.svg" width="100%" /> </p> <p align="center"> <b>Modern, hızlı ve geliştirici dostu GitHub masaüstü yöneticisi</b> </p>
🧠 Overview

GitCan Desktop, GitHub ile etkileşimi tamamen görselleştiren, modern bir masaüstü uygulamasıdır.
Tauri + React mimarisiyle geliştirilmiş olup performans, sadelik ve gerçek kullanım senaryoları odağa alınmıştır.

CLI kullanımını minimuma indirir ve kullanıcıya:

Repo oluşturma
Dosya yükleme
Repo içeriği görüntüleme
GitHub auth yönetimi

gibi işlemleri tek bir arayüzden yapma imkanı sunar.

⚡ Core Features
🔐 GitHub Authentication (Device Flow)
GitHub OAuth Device Flow ile giriş
Güvenli token yönetimi
Local store üzerinde saklama
Tam API tabanlı iletişim
📦 Repository Management
Repo oluşturma (Public / Private)
Repo güncelleme & silme
Kullanıcıya ait repo listeleme
Default branch yönetimi
📁 File & Folder Operations
Local dosya/kalsör seçimi
Recursive kopyalama
Otomatik .gitkeep oluşturma
Güvenli fallback copy sistemi
📂 Explorer System (UI)
Repo içeriğini ağaç yapısında görüntüleme
Klasör navigasyonu
Dosya önizleme (text / html)
Modal tabanlı explorer UI
🚀 Push & Upload Pipeline
Adım adım progress sistemi
Gerçek zamanlı event tabanlı loglar
Yüzdelik ilerleme takibi
Hata yakalama ve raporlama
🖥️ Native Desktop Power (Tauri)
Rust backend ile yüksek performans
Shell komutları çalıştırabilme
Sistem dialog erişimi
Window kontrol yetkileri
🎨 Modern UI / UX
Tam karanlık tema
Minimal ve sade tasarım
Splash screen + loading progress sistemi
Custom alert event sistemi
🧩 Architecture

GitCan Desktop, hybrid modern architecture kullanır:

Frontend
React (Vite)
Component-based yapı
State-driven UI
Event listeners (Tauri bridge)

→ Entry point:


Backend
Rust (Tauri)
File system operations
GitHub API proxy işlemleri
Stream & async işlemler (tokio)
Communication Layer
invoke() ile frontend → backend çağrıları
Event emitter ile progress & log aktarımı
🔐 Security & Permissions
Capability-based permission sistemi
Scoped erişim (shell, dialog, store)
Window bazlı yetkilendirme
🎯 Design Philosophy

GitCan şu prensiplerle geliştirildi:

Zero friction UX → Kullanıcı düşünmeden kullanmalı
Native performance → Electron yerine Tauri
Visual-first Git → CLI yerine arayüz
Modular yapı → kolay genişletilebilir
🔥 Unique Highlights
⚡ Tauri + React hibrit yapı (performans + UI dengesi)
🔐 Device Flow auth (advanced GitHub integration)
📂 Gerçek file system sync (sadece API değil)
📊 Live progress system (event-driven)
🧠 Clean architecture (frontend / backend ayrımı net)
🚧 Future Plans
 Commit / Push granular control
 Branch management
 Drag & Drop upload
 Multi-account support
 Repo diff viewer
 Offline caching
👨‍💻 Developer

Serhat Can
📍 Samsun
🔗 https://github.com/serhatcan44

⭐ Support

Projeyi beğendiysen ⭐ bırakmayı unutma.
Bu proje aktif olarak geliştirilmektedir.
