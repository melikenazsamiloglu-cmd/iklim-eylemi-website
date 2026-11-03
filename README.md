# İklim Eylemi | Climate Action Website 🌱

**İklim Eylemi**, Birleşmiş Milletler Sürdürülebilir Kalkınma Amaçları kapsamında **SKA 13 – İklim Eylemi** konusuna odaklanan, üniversite web tasarımı dersi için hazırlanmış çok sayfalı bir eğitim projesidir. Site; iklim değişikliği, hedefler, çevresel sorunlar ve çözüm önerilerini ziyaretçilere görsel ve etkileşimli bir arayüzle sunar.

**Geliştiren:** Melike Naz Şamiloğlu  
**Proje türü:** Üniversite dersi kapsamında web tasarım projesi (Aralık 2025)  
**Durum:** Statik web sitesi / eğitim amaçlı prototip

## Teknolojiler

- **HTML5:** Sayfa yapısı ve içerik
- **Tailwind CSS (CDN):** Arayüz düzeni ve duyarlı tasarım sınıfları
- **JavaScript:** Sayfa içi etkileşimler, navigasyon ve görsel bileşenler
- **Chart.js (CDN):** Grafiklerin tarayıcıda görselleştirilmesi
- **Google Fonts:** Yazı tipi kaynakları

## Sayfalar

| Dosya | İçerik |
| --- | --- |
| `index.html` | Ana sayfa, proje tanıtımı ve yönlendirme kartları |
| `hedef.html` | İklim hedefleri ve ısınma şeritleri görselleştirmesi |
| `sorunlar.html` | İklim krizinin öne çıkan çevresel ve toplumsal etkileri |
| `cozumler.html` | Sürdürülebilirlik önerileri ve karbon tasarrufu örnek grafiği |
| `uni.html` | Google Forms öğrenci anketine dayanan kampüs sürdürülebilirliği gösterge panosu ve demo görüş formu |

## Teknik özellikler

- Beş sayfadan oluşan statik web sitesi
- Mobil cihazlara uyum sağlamayı hedefleyen menü ve sayfa düzenleri
- Ana sayfada görsel kaydırıcı (slider)
- Chart.js ile grafik çizimleri
- Kampüs görüş formu için **simülasyon arayüzü**
- Google Forms ile toplanan **28 öğrenci yanıtına dayalı** altı veri grafiği
- Katılımcıların kimliğini açığa çıkarmayan, toplulaştırılmış anket özet dosyası (`anket-ozeti.csv`)

## Çalıştırma

1. Depoyu indir veya klonla.
2. `index.html` dosyasını güncel bir web tarayıcısında aç.
3. Üst menüden diğer sayfalara geçiş yap.

Ayrıca GitHub Pages üzerinden **Settings → Pages → Deploy from a branch → `main` → `/(root)`** ile yayımlanabilir. Tailwind CSS, Chart.js ve Google Fonts CDN üzerinden kullanıldığı için **internet bağlantısı gerekir**.

## Google Forms anket çalışması

Üniversitemizdeki Durum bölümünde, öğrencilerin iklim değişikliği ve kampüs sürdürülebilirliği hakkındaki görüşlerini değerlendirmek amacıyla yapılan Google Forms anketi kullanılmıştır.

- **Katılımcı:** 28 öğrenci yanıtı
- **İncelenen temalar:** ulaşım tercihi, iklim değişikliği endişesi, geri dönüşüm olanakları, iklim krizinin nedenleri, yönetim uygulamalarının değerlendirilmesi, derslerde sürdürülebilirlik
- **Örnek bulgular:** 21 katılımcı geri dönüşüm kutularını yetersiz, 5 katılımcı ise hiç kutu görmediğini belirtmiştir. Sürdürülebilirlik konularının derslerde hiç ele alınmadığını belirten 15, çok nadiren ele alındığını belirten 11 öğrenci vardır.
- **Veri kaynağı:** `anket-ozeti.csv` (anonim, toplulaştırılmış)
- **Yöntem ve sınırlamalar:** `anket-yontemi.md`

Bireysel anket yanıtları ve zaman damgaları gizliliği korumak için yayımlanmamıştır.

## Veri ve işlev sınırları

> **Önemli:** `uni.html` üzerindeki altı grafik, Google Forms üzerinden elde edilen **28 öğrenci yanıtından** yeniden hesaplanarak düzeltildi. Grafiklerdeki sayılar sabit (statik) tutulur; ancak kaynağı ve hesaplama yöntemi `anket-ozeti.csv` ve `anket-yontemi.md` dosyalarında belgelenmiştir. Bu sonuçlar sadece katılımcıların görüşlerini yansıtır, üniversitenin tüm öğrencilerini temsil etmez.

- Isınma şeritlerinin renkleri kod içinde dönemlere göre belirlenmiştir; bunlar yıllık ölçülmüş sıcaklık anomalilerinin doğrudan görselleştirilmesi değildir.
- Kampüs görüş formu, `type="button"` ile bir bilgilendirme penceresi açar; veri göndermez veya kaydetmez.
- Site bir bilgilendirme/tasarım prototipidir; güncel ve doğrulanmış iklim istatistikleri için ilgili bilimsel kaynaklara başvurulmalıdır.

## Not

Bu depoda bulunan web sayfalarının **orijinal kaynak kodları korunmuştur**. Bu README, projeyi GitHub portföyünde doğru şekilde açıklamak amacıyla eklenmiştir.
