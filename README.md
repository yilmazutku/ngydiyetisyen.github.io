# NGY Diyetisyen - GitHub Pages Support Site

Bu klasör, **NGY Diyetisyen** uygulamasının App Store yayınlaması için gerekli olan destek ve yasal sayfaları içerir.

## 📋 İçerik

| Dosya | Açıklama | URL Yolu |
|-------|----------|----------|
| `index.html` | Ana destek sayfası (Türkçe) | `/` |
| `index-en.html` | Ana destek sayfası (İngilizce) | `/index-en.html` |
| `privacy-policy.html` | Gizlilik Politikası (Türkçe) | `/privacy-policy.html` |
| `privacy-policy-en.html` | Privacy Policy (English) | `/privacy-policy-en.html` |
| `terms-of-service.html` | Kullanım Koşulları (Türkçe) | `/terms-of-service.html` |
| `terms-of-service-en.html` | Terms of Service (English) | `/terms-of-service-en.html` |
| `_config.yml` | Jekyll yapılandırması | - |

---

## 🚀 GitHub Pages Kurulum Rehberi

### Adım 1: GitHub Repository Oluşturma

1. GitHub'a gidin: https://github.com/new
2. Repository adını girin:
   - **Seçenek A (Önerilen):** `username.github.io` formatında (örn: `ngydiyetisyen.github.io`)
   - **Seçenek B:** Herhangi bir isim (örn: `ngy-support`)
3. Repository'yi **Public** olarak ayarlayın
4. "Create repository" butonuna tıklayın

### Adım 2: Dosyaları Yükleme

#### Seçenek A: GitHub Web Arayüzü (En Kolay)

1. Yeni oluşturduğunuz repository'ye gidin
2. "Add file" → "Upload files" tıklayın
3. Bu klasördeki tüm dosyaları (`.html`, `_config.yml`) sürükleyin
4. "Commit changes" tıklayın

#### Seçenek B: Git Komut Satırı

```bash
# Bu klasöre gidin
cd github_pages

# Git repository başlatın
git init

# Remote ekleyin (URL'yi kendi repository'nizle değiştirin)
git remote add origin https://github.com/USERNAME/REPO-NAME.git

# Dosyaları ekleyin
git add .

# Commit yapın
git commit -m "Add support pages for App Store"

# Push yapın
git push -u origin main
```

### Adım 3: GitHub Pages'i Etkinleştirme

1. Repository'nizin **Settings** sayfasına gidin
2. Sol menüden **Pages** seçeneğine tıklayın
3. **Source** bölümünde:
   - Branch: `main` seçin
   - Folder: `/ (root)` seçin
4. **Save** butonuna tıklayın

### Adım 4: URL'leri Doğrulama

Birkaç dakika bekledikten sonra siteniz hazır olacaktır:

- **User site:** `https://username.github.io/`
- **Project site:** `https://username.github.io/repo-name/`

---

## 📱 App Store Connect'te Kullanım

App Store Connect'te aşağıdaki URL'leri kullanın:

| Alan | URL |
|------|-----|
| **Support URL** (Zorunlu) | `https://username.github.io/` |
| **Privacy Policy URL** (Zorunlu) | `https://username.github.io/privacy-policy.html` |
| **Marketing URL** (İsteğe Bağlı) | `https://username.github.io/` |

> ⚠️ **Önemli:** `username` kısmını kendi GitHub kullanıcı adınızla değiştirin!

---

## ✅ İletişim Bilgileri

Tüm dosyalarda aşağıdaki iletişim bilgileri ayarlanmıştır:

| Alan | Değer |
|------|-------|
| **E-posta** | dytnilaygoktepe@gmail.com |
| **Telefon** | 0533 284 43 33 |
| **Adres** | Cubes Plaza, B Blok No:208, Çukurambar, Öğretmenler Cd. No:6, 06510 Çankaya/Ankara |

Bu bilgiler değişirse, tüm `.html` dosyalarında güncelleyin.

---

## 🔧 Özel Domain (İsteğe Bağlı)

Kendi domain'inizi kullanmak istiyorsanız:

1. `CNAME` adında bir dosya oluşturun
2. İçine domain adınızı yazın (örn: `support.ngydiyetisyen.com`)
3. DNS ayarlarınızda CNAME kaydı ekleyin:
   - Type: `CNAME`
   - Name: `support` (veya kullanmak istediğiniz subdomain)
   - Value: `username.github.io`

---

## 📝 Dosya Yapısı

```
github_pages/
├── _config.yml           # Jekyll yapılandırması
├── index.html            # Ana sayfa (TR) - Support URL
├── index-en.html         # Ana sayfa (EN)
├── privacy-policy.html   # Gizlilik Politikası (TR)
├── privacy-policy-en.html# Privacy Policy (EN)
├── terms-of-service.html # Kullanım Koşulları (TR)
├── terms-of-service-en.html # Terms of Service (EN)
└── README.md             # Bu dosya
```

---

## ✅ Kontrol Listesi

Yayınlamadan önce kontrol edin:

- [ ] Tüm dosyalar GitHub'a yüklendi
- [ ] GitHub Pages etkinleştirildi
- [ ] Site URL'si çalışıyor
- [ ] E-posta adresi güncellendi
- [ ] Telefon numarası güncellendi
- [ ] Adres güncellendi
- [ ] Tüm linkler çalışıyor
- [ ] App Store Connect'e URL'ler girildi

---

## 🆘 Yardım

Sorun yaşarsanız:
- GitHub Pages Docs: https://docs.github.com/en/pages
- Jekyll Docs: https://jekyllrb.com/docs/

---

© 2026 NGY Diyetisyen. Tüm hakları saklıdır.

