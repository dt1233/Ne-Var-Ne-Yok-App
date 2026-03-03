<div align="center">
  <!-- Logoyu klasörde yan yana koyduğunuz logoyla değiştirebilirsiniz (örn: logo.png) -->
  <img src="./Logo.png" alt="Ne Var Ne Yok? Logo" width="200" />
  <h1>🏙️ Ne Var Ne Yok?</h1>
  <p><b>Akıllı Şehir Bilgi ve Ulaşım Takip Platformu</b></p>

  <p>
    <img alt="City App" src="https://img.shields.io/badge/City%20App-Android%20%7C%20iOS-10B981?style=flat-square&logo=appveyor&logoColor=white" />
    <img alt="Transit" src="https://img.shields.io/badge/Public%20Transit-Live%20Tracking-F59E0B?style=flat-square&logo=google-maps&logoColor=white" />
    <img alt="Accessibility" src="https://img.shields.io/badge/Accessibility-Supported-3B82F6?style=flat-square&logo=accessible-icon&logoColor=white" />
    <img alt="Smart City" src="https://img.shields.io/badge/Smart%20City-Integration-8B5CF6?style=flat-square&logo=cityjs&logoColor=white" />
  </p>
</div>

---

## 📖 Proje Özeti
**Ne Var Ne Yok?**, şehir sakinlerinin, turistlerin ve belediye ekiplerinin şehir ile ilgili bilgilere daha hızlı, şeffaf ve kolay erişebilmesini sağlamak amacıyla geliştirilmiş kapsamlı bir akıllı şehir (Smart City) mobil uygulamasıdır. Şehirdeki toplu taşıma araçlarının anlık takibinden, güncel trafik durumuna ve doğrudan belediye ile iletişime kadar pek çok hizmeti tek bir merkezden sunmayı hedefler.

---

## 🚀 Projenin Ana Hedefleri ve Sağlayacağı Yararlar

*   **🚌 Toplu Taşıma Takibi:** Kullanıcıların şehir içi ulaşım planlamasını kolaylaştırmak için otobüslerin anlık konumunu sağlama.
*   **🚦 Anlık Trafik ve Haber Akışı:** Trafik yoğunlukları, yol çalışmaları ve güncel şehir duyurularını sunarak zaman tasarrufu oluşturma.
*   **🤝 Doğrudan İletişim:** Vatandaşların belediyeye ait destek hattıyla hızlıca iletişime geçmesi ve taleplerinin daha pratik işlenmesi.
*   **♿️ Engelli Dostu Sistemler:** Otobüs şoförü ile etkileşime geçen engelli vatandaş bildirim sistemi.
*   **🗺️ Kent Rehberi:** Turistler ve yeni gelen ziyaretçiler için detaylı şehir turizm ve mekân rehberi.

---

## 👥 Hedef Kullanıcılar

1.  **Vatandaşlar:** Günlük şehir içi ulaşım, trafik ve bilgilendirme hizmetlerinden faydalanan temel kitle.
2.  **Turistler:** Şehri ziyaret eden misafirler için kültür, turizm ve mekân bilgilendirmesi.
3.  **Belediye Yetkilileri:** Gelen destek hattı taleplerini değerlendiren ve şehir duyurularını yöneten idari personel.
4.  **Otobüs Şoförleri:** Güzergâh durumu ve duraktaki engelli yolcu bildirimleriyle etkileşim sağlayan operatörler.

---

## 📌 Proje Kapsamı (Scope)

### Fonksiyonel Kapsam
*   **1. Ulaşım Takip Sistemi:** Otobüslerin entegre GPS donanımlarıyla anlık konumu, durak yoğunlukları, hareket saatleri/güzergâhlar ve Engelli Birey Bildirimi.
*   **2. Benim Şehrim:** Şehrin güncel haber ve duyuruları, trafik yoğunluk durumu, yol çalışmaları, açık işletmeler ve nöbetçi eczane listesi.
*   **3. Kent Rehberi:** Şehirdeki tarihi/gezilecek yerler rotası ve turistik rehber entegrasyonu.
*   **4. Destek Hattı:** Vatandaş destek operasyonlarını hızlandıran online talep ve bilet (ticket) sistemi.

### Fonksiyonel Olmayan Kapsam
*   **Performans:** Güncellenmiş verilerin sisteme en fazla *5 saniye* içerisinde yansıması.
*   **Güvenlik:** Kritik kullanıcı verilerinin end-to-end şifrelenmesi ve *OAuth 2.0* tabanlı kimlik doğrulama.
*   **Uyumluluk:** Tamamen cross-platform (Android ve iOS) uyumluluğu.

### Başarı Kriterleri (Kabul Sınırları)
*   Toplu ulaşım ağını kullanan kitlenin ez az **%90'ı** tarafından benimsenme ve günlük kullanım oranı elde etme.
*   Otobüs ve toplu taşıma takip sisteminin GPS servis ağı ile en az **%95 doğruluk** oranında eşzamanlı çalışabilmesi.
*   Belediye idari ekranından aktarılan haberlerin her daim **%100** erişilebilir kalması.
*   Destek hattına düşen vatandaş bildirimlerinin SLA kapsamında en geç **48 saat** içinde işleme alınması.
*   Kullanıcı geribildirimlerinden minimum **%85 memnuniyet** puanı.

---

## 🚫 Proje Sınırları ve Kısıtlamalar
Sistemin mimari tasarımı belirlenirken bazı kesin sınır ve varsayımlar uygulanmıştır:

*   Uygulama herhangi bir **finansal işlem** veya ödeme sistemi modülü (e-cüzdan vb.) barındırmaz.
*   Yalnızca şehir içi toplu taşıma araçları entegrasyonu kapsanmakta olup, özel rent-a-car veya taksi benzeri veriler bulunmaz.
*   Sistem verimliliği tamamen belediye API'lerinden aktarılacak güncel veri döngüsüne ve harita tarafında **Google Maps API**'e bağımlıdır. Kullanıcı tarafında konum verilmesine izin verilmesi gereklidir.

---

## 📥 Proje Demoları ve Görseller
Gizlilik politikaları gereği sistemin içerisinden anlık ekran görüntüleri bu genel dokümantasyonda direkt olarak yer almamaktadır.

> 📌 **İletişim:** NVNY'in algoritma işleyişi, teknik özellikleri, detaylı veri şeması, canlı proje test linkleri ve arayüz görselleri talep edilmesi durumunda karşı tarafa doğrudan PDF ve sunum formatında iletilecektir.

---

<div align="center">
  <p><i>Bu proje,<link>Betsan Teknoloji</link> tarafından geliştirilmiştir.</i></p>
  <p>betsanglobal.com</p>
</div>

