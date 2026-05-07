<div align="center">

# 🔐 google-auth

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/abdulrahmanqdev/google-auth?style=flat-square&color=yellow"/>
  <img src="https://img.shields.io/github/forks/abdulrahmanqdev/google-auth?style=flat-square&color=green"/>
  <img src="https://img.shields.io/github/last-commit/abdulrahmanqdev/google-auth?style=flat-square&color=orange"/>
</p>

<p align="center">
  <strong>Next.js ile Google OAuth kimlik doğrulama entegrasyonu.</strong><br/>
  Güvenli, hızlı ve üretime hazır Google ile giriş şablonu.
</p>

</div>

---

## 📖 Genel Bakış

**google-auth**, Next.js uygulamalarına Google OAuth 2.0 kimlik doğrulamasını entegre etmek için hazırlanmış bir başlangıç şablonudur. NextAuth.js kullanılarak geliştirilmiş olup saniyeler içinde kendi projenize uyarlayabilirsiniz.

---

## ✨ Özellikler

- 🔑 Google OAuth 2.0 entegrasyonu
- 🛡️ Güvenli oturum yönetimi (NextAuth.js)
- ⚡ Next.js App Router uyumlu
- 🎨 Tailwind CSS ile şık giriş ekranı
- 🔒 Korumalı sayfa yönlendirmesi (middleware)
- 📱 Tam responsive tasarım

---

## 🛠️ Teknoloji Yığını

| Teknoloji | Amaç |
|---|---|
| Next.js | Framework |
| NextAuth.js | Kimlik Doğrulama |
| Google OAuth 2.0 | Giriş Sağlayıcısı |
| Tailwind CSS | Stillendirme |

---

## 🚀 Başlarken

### Gereksinimler
- Node.js `>= 18.x`
- Google Cloud Console hesabı ve OAuth 2.0 kimlik bilgileri

### Kurulum

```bash
git clone https://github.com/abdulrahmanqdev/google-auth.git
cd google-auth
npm install
```

### Ortam Değişkenleri

`.env.local` dosyası oluştur:

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

---

## 🔧 Google Cloud Console Ayarları

1. [Google Cloud Console](https://console.cloud.google.com/)'a git
2. Yeni proje oluştur
3. **APIs & Services > Credentials** bölümüne git
4. **OAuth 2.0 Client ID** oluştur
5. Yetkili yönlendirme URI'sı olarak `http://localhost:3000/api/auth/callback/google` ekle

---

## 🤝 Katkıda Bulunma

1. Repoyu fork'la
2. Yeni dal oluştur
3. Değişiklikleri kaydet ve Pull Request aç

---

## 👤 Geliştirici

**@abdulrahmanqdev**
