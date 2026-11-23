<div align="center">

<img src="docs/01-kapak.png" alt="Etkinlik Portalı — Enes Öztürk imzalı proje" width="100%">

# Etkinlik Portalı

**Ödev 6 — etkinlik oluşturma formu, kategori filtreleri, detay görüntüleme ve gereksinim değerlendirme raporu içeren React uygulaması.**

[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/etkinlik-portali)
[![TypeScript](https://img.shields.io/badge/TypeScript-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/etkinlik-portali)
[![Tailwind](https://img.shields.io/badge/Tailwind-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/etkinlik-portali)
[![Frontend](https://img.shields.io/badge/Frontend-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/etkinlik-portali)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/etkinlik-portali)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

Etkinlik Portalı, Patika.dev Node.js/React patikasının 6. ödevidir. Kullanıcı yeni etkinlik oluşturabilir, mevcut etkinlikleri kategoriye göre filtreleyebilir, detaylarını inceleyebilir ve katılım durumunu yönetebilir. Arayüz, ödev kriterlerini tek ekranda denetleyen bir rapor paneli de sunar.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **Yeni Etkinlik Ekle** | Başlık, tarih, konum, kategori ve açıklama alanlı form. |
| **Kategori filtreleri** | Teknoloji, Tasarım & Sanat, Eğitim & Kariyer, Girişimcilik. |
| **Etkinlik kartları** | Yüz yüze / çevrimiçi rozetleri, tarih ve konum bilgisi. |
| **Detay modalı** | Etkinliğin tüm alanlarını tek pencerede gösterir. |
| **Ödev 6 raporu** | Gereksinimlerin karşılanma durumunu denetler. |
| **Örnek veri** | Tek tıkla demo etkinlikleri yükler. |

---

## Kapsam

| Ölçü | Değer |
| --- | --- |
| Ödev | 6 |
| Kategori | 4 |
| Form alanı | 6 |
| Rapor | Anlık |

---

## Galeri

<img src="docs/02-ekran.png" alt="Etkinlik Portalı ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="Etkinlik Portalı etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="Etkinlik Portalı detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/etkinlik-portali.git
cd etkinlik-portali
npm install
npm run dev
```

> Uygulama tamamen istemci tarafında çalışır; API anahtarı gerektirmez.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/components/AddEventForm.tsx   Etkinlik oluşturma
src/components/EventCard.tsx      Kart görünümü
src/components/EventDetailModal.tsx  Detay penceresi
src/components/RubricModal.tsx    Ödev kriterleri
src/data/initialEvents.ts         Örnek veri
src/types/event.ts                Tip tanımları
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
