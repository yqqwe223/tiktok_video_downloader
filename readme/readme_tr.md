# TikTok Video Parser Tool 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Türkçe-yellow.svg)

## 📋 Proje Genel Bakışı

**TikTok Video Parser Tool**, eğitimciler, araştırmacılar ve bireysel öğrenenlerin, "adil kullanım" (Fair Use) ilkeleri çerçevesinde, halka açık TikTok kısa video bağlantılarını arşivleme ve inceleme amaçlarıyla teknik olarak analiz etmelerine yardımcı olmak üzere tasarlanmış web tabanlı bir yardımcı araçtır. Bu araç, öğretim vaka toplama, yeni medya araştırmaları ve kişisel bilgi yönetimi gibi ticari olmayan senaryolar için temiz ve verimli teknik destek sağlamaya odaklanmaktadır.

🔗 **Canlı Demo**: [https://twittervideodownloaderx.com/tiktok_downloader_tu](https://twittervideodownloaderx.com/tiktok_downloader_tu)

> ⚠️ **Önemli Uyarı**: Bu proje yalnızca teknik öğrenme ve araştırma amaçlarıyla geliştirilmiştir. Kullanıcıların, geçerli telif hakkı yasalarına ve platformların hizmet şartlarına uymaları, orijinal içerik üreticilerinin haklarına saygı göstermeleri ve bu aracı, fikri mülkiyet haklarını ihlal eden veya platform politikalarını çiğneyen herhangi bir etkinlik için kullanmaktan kaçınmaları beklenmektedir.

---

## ✨ Temel Özellikler

- 🔗 **Akıllı Bağlantı Tanıma**: Birden fazla TikTok video URL formatını otomatik olarak ayrıştırır
- 📥 **Kalite Uyarlaması**: Kaynak meta verilerine dayanarak mevcut çözünürlük seçeneklerini sunar (platformun kullanılabilirliğine tabidir)
- 📱 **Çoklu Cihaz Uyumluluğu**: Masaüstü ve mobil tarayıcılar için optimize edilmiş duyarlı tasarım
- 🔐 **Gizlilik Odaklı Tasarım**: Kullanıcı etkinlik günlükleri saklanmaz; ayrıştırılan içerik sunucularda tutulmaz
- ⚡ **Hafif ve Hızlı**: İstemci odaklı işleme mantığı, hızlı yanıtlar için sunucu bağımlılığını en aza indirir
- 🔄 **Aktif Bakım**: Platform ön uç değişikliklerine uyum sağlamak ve sürekli işlevsellik sağlamak için düzenli güncellemeler

---

## 🚀 Hızlı Başlangıç Kılavuzu

### Adım 1: Video Bağlantısını Elde Edin
1. TikTok uygulamasını veya web sitesini açın
2. Analiz etmek istediğiniz **halka açık videoyu** bulun
3. "Paylaş" → "Bağlantıyı kopyala" seçeneğine dokunun/tıklayarak video URL'sini kopyalayın

### Adım 2: Ayrıştırma İçin Gönderin
1. Şu adrese gidin: `https://twittervideodownloaderx.com/tiktok_downloader_tu`
2. Kopyaladığınız bağlantıyı belirtilen giriş alanına yapıştırın
3. "Ayrıştırmayı Başlat" düğmesine tıklayın

### Adım 3: Sonuçları İnceleyin
1. Sistemin teknik analizi tamamlamasını bekleyin (genellikle birkaç saniye)
2. Mevcut video meta verileri önizlemesini inceleyin
3. Talimatlara göre sonraki işlemleri gerçekleştirin (yalnızca kişisel öğrenme amaçları için)

---

## 💡 Desteklenen Bağlantı Formatları

```
✅ Önerilen URL kalıpları:
- https://www.tiktok.com/@username/video/1234567890
- https://vm.tiktok.com/xxxxxx/
- https://vt.tiktok.com/xxxxxx/

❌ Şu anda desteklenmeyen senaryolar:
- "Gizli" veya "Yalnızca arkadaşlar" olarak ayarlanmış videolar
- Erişim için kimlik doğrulama veya giriş gerektiren içerikler
- Silinmiş, bölge kısıtlamalı veya yaş kısıtlamalı videolar
- Gelişmiş Dijital Haklar Yönetimi (DRM) ile korunan içerikler
```

---

## ⚙️ Teknik Mimari

| Bileşen | Uygulama | Açıklama |
|-----------|---------------|-------------|
| **Ön Yüz** | HTML5 + CSS3 + Vanilla JS | Hızlı yükleme için çerçevesiz |
| **İstek İşleyici** | Node.js / Python Backend | Eşzamansız engelleyici olmayan, yüksek eşzamanlılık desteği |
| **İçerik Ayrıştırıcı** | Düzenli İfadeler + DOM Analizi | Yalnızca genel meta verileri çıkarır; şifreleme atlatma yok |
| **Güvenlik Katmanı** | HTTPS + Giriş Temizleme + Hız Sınırlama | Kötüye kullanımı önler ve hizmet kararlılığını sağlar |
| **Dağıtım** | Docker + CDN Hızlandırma | Düşük gecikmeli erişim için küresel dağıtılmış düğümler |

---

## ⚠️ Uyumluluk ve Sorumlu Kullanım Beyanı

Bu araç, **teknik tarafsızlık** ve **adil kullanım** ilkeleri çerçevesinde sıkı bir şekilde çalışmaktadır. Lütfen aşağıdaki yönergelere uyunuz:

### ✅ İzin Verilen Kullanım Senaryoları
- 📚 Eğitim kurumlarının akademik vaka çalışmaları için kısa formatlı medyayı analiz etmesi
- 🔗 Halka açık video içeriğinin örneklenmesi ve açıklama eklenmesini içeren araştırma projeleri
- 🗂️ Kişisel içerik üreticilerinin ilham için referans materyalleri düzenlemesi (uygun atıfla)
- 🌐 Sınırlı internet bağlantısı olan bölgelerde çevrimdışı öğrenme erişimi

### ❌ Yasaklanan Etkinlikler
- 🚫 Ayrıştırılan içeriğin ticari dağıtım veya para kazanma amacıyla kullanılması
- 🚫 Filigranları kaldırıp içeriği orijinal çalışma olarak yeniden yayınlamak
- 🚫 Toplu veri kazıma, otomatik veri toplama veya platform operasyonlarını aksatma
- 🚫 Genel olmayan içeriği görüntülemek için erişim kontrollerini atlatmaya çalışmak

### 📜 Yasal Referans Çerçevesi
- Uygulanabilir telif hakkı mevzuatı kapsamında adil kullanım hükümleri (ör. Fikir ve Sanat Eserleri Kanunu)
- Platforma özgü Hizmet Şartları ve Topluluk Kuralları
- Dijital içerik erişimi ve fikri mülkiyeti düzenleyen yerel yasalar

> 📌 **Sorumluluk Reddi**: Geliştiriciler, bu aracın kötüye kullanımından kaynaklanan herhangi bir sorumluluğu üstlenmez. Bu yazılımı kullanarak, yukarıda belirtilen şartları okuduğunuzu, anladığınızı ve bunlara uymayı kabul ettiğinizi beyan etmiş olursunuz.

---

## 🤝 Katkıda Bulunma

Bu projeyi geliştirmeye yardımcı olmak için topluluktan katkıları memnuniyetle karşılıyoruz:

```bash
# 1. Depoyu fork edin
# 2. Bir özellik dalı oluşturun
git checkout -b feature/iyilestirme

# 3. Değişikliklerinizi commit edin
git commit -m "feat: URL desen eşleştirme mantığını iyileştir"

# 4. Push edin ve Pull Request açın
git push origin feature/iyilestirme
```

**Katkı Yönergeleri**:
- ESLint / Prettier kod stili kurallarına uyun
- Yeni işlevsellik için uygulanabilir olduğunda birim testleri ekleyin
- Türkçe veya İngilizce olarak net, açıklayıcı commit mesajları kullanın
- Yeni özellikleri hem kod yorumlarında hem de README güncellemelerinde belgeleyin

---

## 🐛 Sorun Bildirme

Bir hata mı buldunuz veya bir iyileştirme öneriniz mi var?

1. Önce yinelenmeleri önlemek için [Issues](../../issues) sekmesini kontrol edin
2. Yeni bir sorun oluştururken lütfen şunları ekleyin:
   - Tarayıcı adı ve sürümü
   - Adım adım yeniden üretme talimatları
   - Beklenen davranış ile gerçek davranış
   - Ekran görüntüleri veya hata günlükleri (varsa)
3. Ekibimiz gönderimleri düzenli olarak inceler ve mümkün olan en kısa sürede yanıt verir

---

## 📄 Lisans

Bu proje **MIT Lisansı** altında dağıtılmaktadır. Orijinal telif hakkı bildirimi ve lisans koşullarının korunması kaydıyla, bu yazılımı özgürce kullanabilir, değiştirebilir ve dağıtabilirsiniz.

```
MIT License

Copyright (c) 2024 TikTok Video Parser Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Teşekkürler

- Sağlam teknik bileşenler sağlayan açık kaynak topluluğuna minnettarız
- Değerli geri bildirimlerde bulunan kullanıcılara ve araştırmacılara takdirlerimizi sunarız
- Dijital ekosistemi zenginleştiren içerik üreticilerinin çalışmalarını takdir ediyoruz

---

> 📬 **Destek ve İletişim**: Teknik iş birliği soruları veya uyumlulukla ilgili sorular için lütfen GitHub Issues üzerinden bir talep oluşturun. Tüm meşru taleplere hızlı yanıt vermek için çaba gösteriyoruz.

*Bu proje, TikTok Pte. Ltd. veya herhangi bir iştiraki ile bağlantılı, onaylanmış veya desteklenmemektedir. Tüm ticari markalar, logolar ve marka isimleri ilgili sahiplerinin mülkiyetindedir.*