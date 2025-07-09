# Koru Impact Web Sitesi: Vercel ile Yayınlama ve Alan Adı (DNS) Bağlama Rehberi

## 1. Vercel ile Statik Site Yayınlama

1. [Vercel](https://vercel.com) hesabı açın.
2. Proje klasörünüzü GitHub’a yükleyin (tüm HTML, CSS ve diğer dosyalar).
3. Vercel Dashboard’da **“New Project”** butonuna tıklayın.
4. GitHub hesabınızı bağlayın ve ilgili repoyu seçin.
5. **Deploy** butonuna tıklayın.
   - Vercel otomatik olarak build ve deploy işlemini başlatır.
6. Deploy tamamlanınca siteniz `https://<proje-adı>.vercel.app` adresinde yayında olur.

## 2. Özel Alan Adı (koruimpact.org) Bağlama ve DNS Ayarları

1. Vercel Dashboard’da projenizi seçin.
2. **Settings → Domains** menüsüne girin.
3. **“Add”** butonuna tıklayın ve `koruimpact.org` yazıp ekleyin.
4. Vercel size DNS ayarları için gerekli bilgileri gösterecek:
   - **CNAME kaydı:**
     - Ad: `www`
     - Değer: `<proje-adı>.vercel.app`
   - **A kaydı (isteğe bağlı):**
     - Ad: `@`
     - Değer: Vercel’in verdiği IP adresi (genellikle CNAME yeterlidir)
5. Alan adı sağlayıcınızın (ör. IONOS, GoDaddy, Google Domains) DNS yönetimine girin.
6. Yukarıdaki CNAME ve/veya A kayıtlarını ekleyin.
7. DNS değişiklikleri genellikle 5-30 dakika içinde aktif olur (bazen 24 saate kadar sürebilir).
8. Vercel otomatik olarak SSL (https) sertifikası kurar.

---

**Kısa Notlar:**
- Alan adınızın köküne (`@`) A kaydı, `www` için CNAME kaydı eklemeniz önerilir.
- Tüm DNS işlemleri tamamlandığında siteniz `https://koruimpact.org` ve `https://www.koruimpact.org` adreslerinden erişilebilir olur.
- Vercel ve alan adı sağlayıcınızın dökümantasyonunda “Custom Domain” veya “Add Domain” başlıklarına bakarak ekran görüntülü rehberlere ulaşabilirsiniz. 