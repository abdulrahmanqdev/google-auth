<div align="center">

# 🔐 google-auth

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/abdulrahmanqdev/google-auth?style=flat-square&color=yellow"/>
  <img src="https://img.shields.io/github/forks/abdulrahmanqdev/google-auth?style=flat-square&color=green"/>
  <img src="https://img.shields.io/github/last-commit/abdulrahmanqdev/google-auth?style=flat-square&color=orange"/>
</p>

<p align="center">
  <strong>React ve Next.js ile Google OAuth giriş sistemi.</strong><br/>
  NextAuth.js, App Router ve SessionProvider ile hazır kimlik doğrulama şablonu.
</p>

</div>

---

## 📖 Genel Bakış

**google-auth**, Next.js App Router kullanılarak Google OAuth 2.0 entegrasyonunu gösteren bir başlangıç şablonudur. NextAuth.js ile oturum yönetimi, `SessionProvider` ile client-side oturum erişimi ve korumalı dashboard sayfası içerir.

---

## ✨ Özellikler

- 🔑 Google OAuth 2.0 entegrasyonu
- 🛡️ NextAuth.js ile güvenli oturum yönetimi
- ⚡ Next.js App Router uyumlu
- 🔌 `SessionProvider` ile client-side oturum erişimi
- 🔒 Korumalı dashboard sayfası
- 🎨 Tailwind CSS ile modern arayüz
- 📱 Tam responsive tasarım

---

## 🛠️ Teknoloji Yığını

| Teknoloji | Amaç |
|---|---|
| Next.js (App Router) | Framework |
| NextAuth.js | Kimlik Doğrulama |
| Google OAuth 2.0 | Giriş Sağlayıcısı |
| JavaScript | Dil |
| Tailwind CSS | Stillendirme |

---

## 🚀 Başlarken

### Gereksinimler
- Node.js `>= 18.x`
- [Google Cloud Console](https://console.cloud.google.com) üzerinden OAuth 2.0 kimlik bilgileri

### Kurulum

```bash
git clone https://github.com/abdulrahmanqdev/google-auth.git
cd google-auth
npm install
```

### Ortam Değişkenleri

`.env.local` dosyası oluştur ve Google bilgilerini gir:

```env
GOOGLE_CLIENT_ID=google_client_id_buraya
GOOGLE_CLIENT_SECRET=google_client_secret_buraya
NEXTAUTH_SECRET=rastgele_gizli_anahtar
NEXTAUTH_URL=http://localhost:3000
```

### Çalıştır

```bash
npm run dev
```

Tarayıcında [http://localhost:3000](http://localhost:3000) adresini aç.

---

## 🔧 Google Cloud Console Ayarları

1. [Google Cloud Console](https://console.cloud.google.com)'a git
2. Yeni proje oluştur
3. **APIs & Services > Credentials** bölümüne git
4. **OAuth 2.0 Client ID** oluştur
5. Yetkili yönlendirme URI'sı olarak şunu ekle:
   ```
   http://localhost:3000/api/auth/callback/google
   ```

---

## 📁 Proje Yapısı

```
google-auth/
├── src/
│   └── app/
│       ├── api/
│       │   └── auth/
│       │       └── [...nextauth]/
│       │           └── route.js        # NextAuth yapılandırması
│       ├── dashboard/
│       │   └── page.jsx                # Korumalı sayfa
│       ├── providers/
│       │   └── SessionProvider.js      # Client oturum sağlayıcısı
│       ├── favicon.ico
│       ├── globals.css
│       ├── layout.js                   # Root layout
│       └── page.js                     # Ana sayfa (giriş ekranı)
├── .gitignore
├── jsconfig.json
├── next.config.mjs
├── postcss.config.mjs
├── package.json
└── LICENSE
```

---

## 🤝 Katkıda Bulunma

1. Repoyu fork'la
2. Yeni dal oluştur (`git checkout -b ozellik/yeni-ozellik`)
3. Değişiklikleri kaydet ve Pull Request aç

---

## 👤 Geliştirici

**@abdulrahmanqdev**
