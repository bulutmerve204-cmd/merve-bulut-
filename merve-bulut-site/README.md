# Merve Bulut · Kişisel Web Sitesi

Tek sayfalık, Türkçe/İngilizce kişisel akademik site. Hiçbir kurulum, veritabanı veya ücretli servis gerektirmez.

## Klasörde neler var

| Dosya | Ne işe yarar |
|---|---|
| `index.html` | Sitenin tüm içeriği, tasarımı ve kodu |
| `assets/merve-bulut.jpg`, `.webp` | Profil fotoğrafı |
| `assets/Merve-Bulut-CV.pdf` | "CV'mi indir" butonunun açtığı CV |
| `assets/og-image.jpg` | Link WhatsApp/LinkedIn'de paylaşılınca görünen önizleme görseli |
| `assets/apple-touch-icon.png`, `favicon.svg` | Tarayıcı sekmesi ve telefon ana ekranı simgesi |
| `robots.txt`, `sitemap.xml` | Google'ın siteyi bulmasına yardımcı olur |

## Yayına alma (ücretsiz, yaklaşık 10 dakika)

1. **GitHub'da depo aç:** github.com → sağ üstte **+** → **New repository** → isim: `merve-bulut` → **Public** seçili kalsın → **Create repository**.
2. **Dosyaları yükle:** Açılan sayfada **uploading an existing file** bağlantısına tıkla. Zip'i açtığın klasörün *içindeki* her şeyi (index.html, assets klasörü vb.) sürükleyip bırak → **Commit changes**.
3. **Vercel'e bağla:** vercel.com → **Sign Up** → **Hobby** → **Continue with GitHub**. Sonra **Add New… → Project** → `merve-bulut` deposunun yanındaki **Import** → hiçbir ayarı değiştirmeden **Deploy**.
4. Siten `https://merve-bulut.vercel.app` adresinde yayında. Vercel farklı bir adres verirse `index.html`, `robots.txt` ve `sitemap.xml` içindeki `merve-bulut.vercel.app` ifadesini yeni adresle değiştir.

## Sonradan güncelleme

GitHub'da dosyayı aç → kalem simgesi (**Edit**) → değiştir → **Commit changes**. Vercel siteyi bir dakika içinde kendiliğinden günceller.

- **Metinler:** Her metnin Türkçe ve İngilizce hali yan yana durur: `<span lang="tr">…</span><span lang="en">…</span>`. Birini değiştirirken diğerini de güncelle.
- **CV:** Yeni CV'yi aynı adla (`Merve-Bulut-CV.pdf`) `assets` klasörüne yükle.
- **Dil bağlantısı:** İngilizce sürümü doğrudan paylaşmak için adresin sonuna `?lang=en` ekle. Ziyaretçinin tarayıcısı Türkçe değilse site zaten İngilizce açılır.
