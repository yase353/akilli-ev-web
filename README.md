# Akıllı Ev NILM — Web Arayüzü

IoT tabanlı NILM sisteminin Flutter ile geliştirilmiş web ve mobil kullanıcı arayüzü. Gerçek zamanlı enerji tüketimi, AI cihaz tespiti ve tahmini fatura bilgisini kullanıcıya sunar.

## Özellikler

- Anlık güç tüketimi takibi (5 saniyede bir güncelleme)
- AI destekli cihaz tespiti (CNN-LSTM model)
- Buzdolabı ve televizyon bazlı tüketim izleme
- 15 günlük cihaz tüketim dağılımı (pasta grafik)
- Zaman serisi tüketim grafiği (1s / 6s / 1g / 3g)
- Bu gidişle aylık tahmini fatura (günlük ortalama × 30)
- Android APK + Web tarayıcı desteği

## Teknoloji

Flutter (Dart) · fl_chart · GitHub Pages

## Backend

Bu arayüz aşağıdaki backend API'yi kullanır:  
https://github.com/yase353/akilli_ev_nilm

## Canlı Demo

https://yase353.github.io/akilli-ev-web/

## Kurulum (Yerel)

```bash
flutter pub get
flutter run -d chrome
```

Web build almak için:
```bash
flutter build web --base-href /akilli-ev-web/
```

## İlgili Repo

Backend & Model: [akilli_ev_nilm](https://github.com/yase353/akilli_ev_nilm)
