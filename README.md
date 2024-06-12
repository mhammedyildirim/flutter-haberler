
# TR - Flutter Haber Uygulaması - README

## Proje Açıklaması ve Ders Bilgileri

Bu proje, kullanıcıların güncel haberleri takip edebileceği, arayabileceği ve favorilerine ekleyebileceğ bir haber uygulamasıdır. Uygulama, Flutter kullanılarak geliştirilmiş ve RESTful API ile entegre edilmiştir. Uygulamanın amacı, kullanıcı deneyimini iyileştirerek haber okuma alışkanlıklarını daha etkili ve kullanıcı dostu hale getirmektir. State management için Riverpod kullanılmıştır. API kaynağı olarak https://newsapi.org/ kullanılmıştır.

**Erciyes Üniversitesi Bilgisayar Mühendisliği**

**Mobile Application Development Dersi**

**Dr. Öğr. Üyesi FEHİM KÖYLÜ**

## İçindekiler

1. [Giriş](#giriş)
2. [Özellikler](#özellikler)
3. [Uygulama Ekranı](#uygulama-ekranı)
4. [Kurulum](#kurulum)
5. [Kullanım](#kullanım)
6. [Proje Yapısı](#proje-yapısı)
7. [Teknolojiler](#teknolojiler)
8. [Katkıda Bulunma](#katkıda-bulunma)

## Giriş

Haber platformlarının kullanıcı odaklı iyileştirilmesi, son kullanıcı deneyiminin geliştirilmesi açısından büyük önem taşımaktadır. Bu proje, haberlerin kategorilere ayrılması, aranması ve favorilere eklenmesi gibi temel işlevlerle kullanıcı memnuniyetini artırmayı hedeflemektedir. Ayrıca, kullanıcıların ilgilendikleri içeriklere hızlı erişim sağlayarak haber okuma deneyimini zenginleştirmeyi amaçlamaktadır.

## Özellikler

- **Ana Ekran:** Gerçek zamanlı haber akışı sağlar.
- **Arama Fonksiyonu:** Kullanıcıların belirli haberleri aramasına olanak tanır.
- **Haber İçeriği Görüntüleme:** Detaylı haber içeriği sunar.
- **Favorilere Ekleme:** Kullanıcılar favori haberlerini kaydedebilir.
- **Favori Haberleri Görüntüleme ve Paylaşma:** Kullanıcılar favori haberlerini görüntüleyebilir ve paylaşabilir.

## Uygulama Ekranı
![1](https://github.com/mhammedyildirim/flutter-haberler/assets/61433710/ac32d5a6-4649-42f5-bc74-a42083908556)

## Kurulum

### Gereksinimler

- Flutter SDK
- Android Studio veya VS Code
- Bir Android veya iOS cihazı ya da emulatorü

### Adımlar

1. **Flutter SDK'yı Kurun:**
   [Flutter SDK İndirme ve Kurulum](https://flutter.dev/docs/get-started/install)

2. **Proje Dosyalarını Kopyalayın:**

   ```
   git clone https://github.com/kullaniciadi/flutter-haber-uygulamasi.git
   ```
   
   ```
   cd flutter-haber-uygulamasi
   ```

4. **Bağımlılıkları Yükleyin:**
   ```
   flutter pub get
   ```

5. **Uygulamayı Çalıştırın:**
   ```
   flutter run
   ```

## Kullanım

Uygulamayı başlattıktan sonra ana ekranda güncel haberler görüntülenecektir. Haberleri arayabilir, detaylarını görüntüleyebilir ve favorilerinize ekleyebilirsiniz. Favori haberlerinizi favoriler sekmesinden görüntüleyebilir ve paylaşabilirsiniz.

## Proje Yapısı

```
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
```

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

***************************************************************************************************************************************************************************

# ENG - Flutter News Application - README

## Project Description and Course Information

This project is a news application where users can follow, search for, and add their favorite news. It is developed using Flutter and integrated with a RESTful API. The aim of the application is to improve the user experience and make news reading habits more effective and user-friendly. Riverpod is used for state management. The API source is https://newsapi.org/.

**Erciyes University Computer Engineering**

**Mobile Application Development Course**

**Asst. Prof. FEHİM KÖYLÜ**

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Application Screens](#application-screens)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Technologies](#technologies)
8. [Contributing](#contributing)

## Introduction

Improving user-centered news platforms is crucial for enhancing the end-user experience. This project aims to increase user satisfaction with basic functions such as categorizing, searching, and adding news to favorites. Additionally, it aims to enrich the news reading experience by providing quick access to the content users are interested in.

## Features

- **Home Screen:** Provides real-time news feed.
- **Search Function:** Allows users to search for specific news.
- **News Content Viewing:** Offers detailed news content.
- **Add to Favorites:** Users can save their favorite news.
- **View and Share Favorite News:** Users can view and share their favorite news.

## Application Screens
![1](https://github.com/mhammedyildirim/flutter-haberler/assets/61433710/ac32d5a6-4649-42f5-bc74-a42083908556)

## Installation

### Requirements

- Flutter SDK
- Android Studio or VS Code
- An Android or iOS device or emulator

### Steps

1. **Install Flutter SDK:**
   [Download and Install Flutter SDK](https://flutter.dev/docs/get-started/install)

2. **Clone the Project Files**

   ```
   git clone https://github.com/kullaniciadi/flutter-haber-uygulamasi.git
   ```
   
   ```
   cd flutter-haber-uygulamasi
   ```

4. **Install Dependencies:**
   ```
   flutter pub get
   ```

5. **Run the app**
   ```
   flutter run
   ```

## Usage

After launching the application, the home screen will display the latest news. You can search for news, view details, and add them to your favorites. You can view and share your favorite news from the favorites tab.

## Project Structure

```
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
```


- **main.dart:** The entry point of the application.
- **models/news.dart:** News model.
- **screens:** The screens of the application.
- **services/api_service.dart:** API services.
- **widgets:** Reusable components within the application.

## Technologies

- **Flutter:** Framework for developing user interfaces.
- **Dart:** Programming language for Flutter.
- **RESTful API:** API used to provide news data.

## Contributing

If you would like to contribute, please send a pull request or open an issue. Your contributions are welcome.
3. **Clone the Project Files:**

