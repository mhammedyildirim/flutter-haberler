
# Flutter Haber Uygulaması - README

## Proje Açıklaması

Bu proje, kullanıcıların güncel haberleri takip edebileceği, arayabileceği ve favorilerine ekleyebileceği bir haber uygulamasıdır. Uygulama, Flutter kullanılarak geliştirilmiş ve RESTful API ile entegre edilmiştir. Uygulamanın amacı, kullanıcı deneyimini iyileştirerek haber okuma alışkanlıklarını daha etkili ve kullanıcı dostu hale getirmektir.

## İçindekiler

1. [Giriş](#giriş)
2. [Özellikler](#özellikler)
3. [Kurulum](#kurulum)
4. [Kullanım](#kullanım)
5. [Proje Yapısı](#proje-yapısı)
6. [Teknolojiler](#teknolojiler)
7. [Katkıda Bulunma](#katkıda-bulunma)
8. [Lisans](#lisans)

## Giriş

Haber platformlarının kullanıcı odaklı iyileştirilmesi, son kullanıcı deneyiminin geliştirilmesi açısından büyük önem taşımaktadır. Bu proje, haberlerin kategorilere ayrılması, aranması ve favorilere eklenmesi gibi temel işlevlerle kullanıcı memnuniyetini artırmayı hedeflemektedir. Ayrıca, kullanıcıların ilgilendikleri içeriklere hızlı erişim sağlayarak haber okuma deneyimini zenginleştirmeyi amaçlamaktadır.

## Özellikler

- **Ana Ekran:** Gerçek zamanlı haber akışı sağlar.
- **Arama Fonksiyonu:** Kullanıcıların belirli haberleri aramasına olanak tanır.
- **Haber İçeriği Görüntüleme:** Detaylı haber içeriği sunar.
- **Favorilere Ekleme:** Kullanıcılar favori haberlerini kaydedebilir.
- **Favori Haberleri Görüntüleme ve Paylaşma:** Kullanıcılar favori haberlerini görüntüleyebilir ve paylaşabilir.

## Kurulum

### Gereksinimler

- Flutter SDK
- Android Studio veya VS Code
- Bir Android veya iOS cihazı ya da emulatorü

### Adımlar

1. **Flutter SDK'yı Kurun:**
   [Flutter SDK İndirme ve Kurulum](https://flutter.dev/docs/get-started/install)

2. **Proje Dosyalarını Kopyalayın:**
   \```bash
   git clone https://github.com/kullaniciadi/flutter-haber-uygulamasi.git
   cd flutter-haber-uygulamasi
   \```

3. **Bağımlılıkları Yükleyin:**
   \```bash
   flutter pub get
   \```

4. **Uygulamayı Çalıştırın:**
   \```bash
   flutter run
   \```

## Kullanım

Uygulamayı başlattıktan sonra ana ekranda güncel haberler görüntülenecektir. Haberleri arayabilir, detaylarını görüntüleyebilir ve favorilerinize ekleyebilirsiniz. Favori haberlerinizi favoriler sekmesinden görüntüleyebilir ve paylaşabilirsiniz.

## Proje Yapısı

\```plaintext
lib/
├── main.dart
├── models/
│   └── news.dart
├── screens/
│   ├── home_screen.dart
│   ├── search_screen.dart
│   ├── favorites_screen.dart
│   └── news_detail_screen.dart
├── services/
│   └── api_service.dart
└── widgets/
    ├── news_card.dart
    └── search_bar.dart
\```

- **main.dart:** Uygulamanın giriş noktası.
- **models/news.dart:** Haber modeli.
- **screens:** Uygulamanın ekranları.
- **services/api_service.dart:** API servisleri.
- **widgets:** Uygulama içinde tekrar kullanılabilir bileşenler.

## Teknolojiler

- **Flutter:** Kullanıcı arayüzü geliştirme framework'ü.
- **Dart:** Flutter için programlama dili.
- **RESTful API:** Haber verilerini sağlamak için kullanılan API.

## Katkıda Bulunma

Katkıda bulunmak isterseniz lütfen bir pull request gönderin ya da bir issue açın. Katkılarınız memnuniyetle karşılanacaktır.
