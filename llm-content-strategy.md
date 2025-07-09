# Koru Impact: LLM ile Web Sitesi İçerik Üretim Stratejisi

## 🎯 Strateji Özeti

Bu dokümantasyon, Koru Impact danışmanlık şirketi için büyük dil modellerini (LLM) kullanarak profesyonel, ilgi çekici ve marka arketiplerine uygun web sitesi metinleri üretme stratejisini açıklar.

## 🏛️ Marka Arketipleri: Sage-Caregiver-Hero

### **Sage (Bilge) Arketipi**
- **Özellikler:** Bilgelik, deneyim, rehberlik, derin anlayış
- **Tone:** Yetkili, düşünceli, analitik, güvenilir
- **Anahtar Kelimeler:** Uzmanlık, metodoloji, analiz, strateji, bilimsel yaklaşım

### **Caregiver (Bakım Veren) Arketipi**
- **Özellikler:** Koruma, destek, empati, toplumsal sorumluluk
- **Tone:** Sıcak, destekleyici, anlayışlı, koruyucu
- **Anahtar Kelimeler:** Destek, koruma, toplumsal fayda, sürdürülebilirlik, etki

### **Hero (Kahraman) Arketipi**
- **Özellikler:** Dönüşüm, liderlik, cesaret, sonuç odaklılık
- **Tone:** Güçlü, kararlı, ilham verici, aksiyon odaklı
- **Anahtar Kelimeler:** Dönüşüm, liderlik, başarı, etki, değişim

## 🤖 LLM Prompt Yazım Stratejisi

### **1. Temel Prompt Yapısı**

```
[ROLE] + [CONTEXT] + [TASK] + [CONSTRAINTS] + [OUTPUT FORMAT]
```

**Örnek Prompt Yapısı:**
```
Sen sosyal bilim temelli danışmanlık alanında uzmanlaşmış bir içerik yazarısın. 
Koru Impact şirketi için [SAYFA_ADI] sayfası metni yazacaksın.

Marka Arketipleri: Sage (bilgelik), Caregiver (koruma), Hero (dönüşüm)
Hedef Kitle: Kurumsal karar vericiler, sosyal sorumluluk yöneticileri
Tone: Profesyonel, güvenilir, ilham verici

Görev: [SPESİFİK_GÖREV]
Kısıtlamalar: [KELİME_LİMİTİ, TEKNİK_DETAYLAR]
Çıktı Formatı: [HTML, MARKDOWN, vb.]
```

### **2. Sayfa Bazlı Prompt Örnekleri**

#### **Ana Sayfa Hero Section**
```
Sen Koru Impact için ana sayfa hero section metni yazacaksın.

Konteks:
- Sosyal bilim temelli danışmanlık
- Kurumların sosyal etkisini maksimize etme
- Sage-Caregiver-Hero arketipleri

Görev:
- Ana başlık (H1): 6-8 kelime, güçlü ve akılda kalıcı
- Alt başlık: 15-20 kelime, değer önerisi
- CTA buton metni: Aksiyon odaklı

Kısıtlamalar:
- Türkçe
- Kurumsal ama samimi tone
- Hero arketipi ağırlıklı

Çıktı: JSON formatında
```

#### **Hizmetler Sayfası**
```
Sen Koru Impact'in hizmetler sayfası için detaylı açıklamalar yazacaksın.

Konteks:
- Sosyal Etki Değerlendirmesi
- KSS Stratejisi
- Araştırma & Analiz

Görev:
Her hizmet için:
- Başlık (H2)
- Kısa açıklama (50-75 kelime)
- Faydalar listesi (3-4 madde)
- Metodoloji özeti

Kısıtlamalar:
- Sage arketipi ağırlıklı
- Teknik ama anlaşılır
- Müşteri faydası odaklı

Çıktı: Markdown formatında
```

### **3. Arketip Bazlı Prompt Teknikleri**

#### **Sage Arketipi için Prompt**
```
[ROLE] + "Sosyal bilimler alanında 20+ yıl deneyimli bir uzman olarak" + [TASK] + "Bilimsel metodoloji ve kanıt temelli yaklaşım vurgulayarak"
```

#### **Caregiver Arketipi için Prompt**
```
[ROLE] + "Toplumsal fayda ve sürdürülebilirlik konusunda tutkulu bir danışman olarak" + [TASK] + "Empati ve koruma temasını öne çıkararak"
```

#### **Hero Arketipi için Prompt**
```
[ROLE] + "Kurumsal dönüşüm ve sosyal etki konusunda lider bir stratejist olarak" + [TASK] + "Dönüşüm ve başarı vurgulayarak"
```

## 📝 İçerik Üretim Süreci

### **Faz 1: Araştırma ve Hazırlık**
1. **Rakip Analizi:** Benzer şirketlerin web sitesi metinlerini incele
2. **Anahtar Kelime Araştırması:** SEO odaklı kelime seçimi
3. **Hedef Kitle Profili:** Detaylı persona oluşturma
4. **Marka Ses Kılavuzu:** Tone, stil, terminoloji belirleme

### **Faz 2: Prompt Mühendisliği**
1. **Temel Prompt Oluşturma:** Sayfa bazlı ana prompt yazma
2. **Arketip Entegrasyonu:** Sage-Caregiver-Hero dengesi kurma
3. **Kısıtlama Belirleme:** Kelime limiti, tone, format
4. **Test ve İyileştirme:** Farklı prompt varyasyonları deneme

### **Faz 3: İçerik Üretimi**
1. **LLM ile İlk Taslak:** Ana prompt ile metin üretimi
2. **Çoklu Versiyon:** Farklı arketip ağırlıkları ile alternatifler
3. **A/B Test Hazırlığı:** Farklı yaklaşımlar için varyasyonlar
4. **Teknik Doğruluk:** Sosyal bilim terminolojisi kontrolü

### **Faz 4: Düzenleme ve Optimizasyon**
1. **İnsan Düzenlemesi:** LLM çıktısını marka sesine uyarlama
2. **SEO Optimizasyonu:** Anahtar kelime yoğunluğu ayarlama
3. **Tone Tutarlılığı:** Arketip dengesi kontrolü
4. **CTA Optimizasyonu:** Dönüşüm odaklı düzenlemeler

## 🎨 Prompt Yazım Teknikleri

### **1. Few-Shot Learning**
```
Örnek 1: [BAŞARILI_METİN_ÖRNEĞİ]
Örnek 2: [BAŞARILI_METİN_ÖRNEĞİ]
Görev: [BENZER_GÖREV]
```

### **2. Chain of Thought**
```
Adım 1: Hedef kitleyi analiz et
Adım 2: Ana mesajı belirle
Adım 3: Arketip dengesini kur
Adım 4: Metni yaz
```

### **3. Role-Based Prompting**
```
Sen [SPESİFİK_ROL] olarak [GÖREV] gerçekleştireceksin.
Bu rolün özellikleri: [ROL_ÖZELLİKLERİ]
Bu rolün deneyimi: [ROL_DENEYİMİ]
```

### **4. Constraint-Based Prompting**
```
Kısıtlama 1: [KELİME_LİMİTİ]
Kısıtlama 2: [TONE_GEREKSİNİMLERİ]
Kısıtlama 3: [TEKNİK_SEVİYE]
Kısıtlama 4: [ARKETİP_AĞIRLIĞI]
```

## 🔍 İçerik Kontrol ve Düzenleme Süreci

### **1. Kalite Kontrol Listesi**
- [ ] Marka arketiplerine uygunluk
- [ ] Teknik doğruluk
- [ ] SEO optimizasyonu
- [ ] Tone tutarlılığı
- [ ] CTA etkinliği
- [ ] Mobil uyumluluk

### **2. Arketip Dengesi Kontrolü**
```
Sage Öğeleri: %40 (uzmanlık, metodoloji)
Caregiver Öğeleri: %30 (koruma, destek)
Hero Öğeleri: %30 (dönüşüm, liderlik)
```

### **3. A/B Test Stratejisi**
- **Versiyon A:** Sage ağırlıklı
- **Versiyon B:** Hero ağırlıklı
- **Versiyon C:** Caregiver ağırlıklı
- **Versiyon D:** Dengeli yaklaşım

### **4. İnsan Düzenleme Teknikleri**
1. **Makro Düzenleme:** Yapı ve akış kontrolü
2. **Mikro Düzenleme:** Kelime seçimi ve cümle yapısı
3. **Tone Ayarlama:** Arketip dengesi ince ayarı
4. **CTA Optimizasyonu:** Dönüşüm odaklı düzenlemeler

## 📊 Performans Ölçümü

### **Metrikler**
- **Sayfa Görüntüleme Süresi:** İçerik kalitesi göstergesi
- **Bounce Rate:** İçerik ilgi çekiciliği
- **CTA Tıklama Oranı:** Aksiyon odaklılık
- **Form Doldurma Oranı:** Dönüşüm etkinliği
- **SEO Sıralaması:** Arama motoru performansı

### **Optimizasyon Döngüsü**
1. **Veri Toplama:** Kullanıcı davranışları
2. **Analiz:** Performans değerlendirmesi
3. **Hipotez:** İyileştirme önerileri
4. **Test:** A/B testleri
5. **Uygulama:** Başarılı değişiklikler

## 🛠️ Teknik Araçlar ve Platformlar

### **LLM Platformları**
- **ChatGPT (GPT-4):** Genel içerik üretimi
- **Claude (Anthropic):** Analitik içerik
- **Bard (Google):** SEO odaklı içerik
- **Perplexity:** Araştırma destekli içerik

### **Prompt Yönetimi**
- **Notion:** Prompt kütüphanesi
- **Airtable:** İçerik takibi
- **Google Docs:** İşbirliği
- **GitHub:** Versiyon kontrolü

### **İçerik Analizi**
- **Grammarly:** Dil kontrolü
- **Hemingway Editor:** Okunabilirlik
- **Yoast SEO:** SEO optimizasyonu
- **Hotjar:** Kullanıcı davranışı

## 🎯 Sonuç

Bu strateji, Koru Impact için LLM kullanarak profesyonel, arketip odaklı ve dönüşüm yaratıcı web sitesi metinleri üretmeyi sağlar. Sürekli test ve optimizasyon ile içerik kalitesi sürekli iyileştirilebilir.

---

*Bu dokümantasyon, LLM ile içerik üretim sürecinin temel çerçevesini oluşturur ve proje ihtiyaçlarına göre güncellenebilir.* 