# Portfolio & AdMob Verification Site

Bu proje **azizonuktav.github.io** GitHub Pages sitesinin kaynak kodlarını içerir.

## 📁 Proje Yapısı

- **index.html**: Ana sayfa (Portfolio)
- **style.css**: Hack'n Roll tema stilleri
- **app-ads.txt**: AdMob doğrulama dosyası (Google Play & AdMob verification için kritik)

## 🚀 Deployment

Bu proje GitHub Pages üzerinde barındırılmaktadır. Değişiklikleri yayına almak için:

```bash
git add .
git commit -m "Update site"
git push origin main
```

## 🤖 Agent Notları (Devralacak Kişi İçin)

### Mevcut Durum
- **Tema:** "Hack'n Roll" (Cybersecurity & Development odaklı dark tema).
- **Teknoloji:** Saf HTML/CSS (Framework yok, bu yüzden hafiftir).
- **Durum:** Yayında (https://azizonuktav.github.io).

### Gelecek Planları / Yapılacaklar
1. **Blog Sistemi:** Şu an "Blog" bölümü statik HTML kartlardan oluşuyor. Gelecekte Jekyll veya Hugo gibi bir SSG (Static Site Generator) ile entegre edilebilir veya basit bir Markdown parser eklenebilir.
2. **Projects Bölümü:** "Applications" kısmı şu an sadece Gitar Akorları'nı içeriyor. Diğer projeler eklenebilir.
3. **SEO:** Meta tagler eklendi ancak daha detaylı SEO çalışması yapılabilir.
4. **Analitik:** Google Analytics vb. eklenmedi.

### Önemli Hatırlatma
- `app-ads.txt` dosyası **ROOT** dizinde kalmalıdır. Alt klasöre taşınırsa AdMob doğrulamasını kaybeder.
- Google Play Store'da uygulamanın website adresi `https://azizonuktav.github.io` olarak kalmalıdır.

### Renk Paleti
- **Background:** `#050510` (Very Dark Blue)
- **Card Background:** `#101025`
- **Accent (Green):** `#00ff88`
- **Secondary (Blue):** `#00d9ff`
