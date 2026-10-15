---
title: Gizlilik Politikası
permalink: /gizlilik
---

# Kaça Patlar — Gizlilik Politikası

Son güncelleme: 15 Ekim 2026

Kaça Patlar bir yolculuğun otoyol, köprü, tünel, yakıt ve şarj masrafını hesaplar. Uygulamanın bir sunucusu, hesap sistemi, reklamı ve analitiği yoktur. Geliştirici olarak sizinle ilgili hiçbir veriyi toplamıyor, saklamıyor ve kimseyle paylaşmıyoruz.

## Konum

- Konumunuz yalnızca izin verirseniz ve yalnızca şu durumlarda kullanılır: rotayı bulunduğunuz yerden başlatmak, yakıt fiyatını bulunduğunuz ile göre almak ve "Yolculuğu başlat"a dokunduktan sonra Canlı Etkinlik'te kalan gişeleri ve tutarı güncellemek.
- Yolculuk takibi, siz "Yolculuğu bitir"e dokununca ya da yolculuk tamamlanınca durur. Ekran kapalıyken de sürmesi için arka planda konum kullanılır; bu sırada iOS durum çubuğunda konum göstergesi görünür.
- Konumunuz cihazda işlenir ve geliştiriciye gönderilmez. Yolculuk takibindeki konum kaydedilmez. Rotayı bulunduğunuz yerden başlattıysanız başlangıç noktası rotanın bir parçası olarak saklanabilir: son rota widget'ı için yalnız bu cihazda, kaydettiğiniz masraf bölüşmelerinin rota bağlantısında ise cihazınızda ve iCloud'unuzda. Rota bağlantısındaki koordinatlar yaklaşık 11 metreye yuvarlanır.

## Cihazınızda ve iCloud'unuzda saklananlar

- Garajınızdaki araçlar, yakıt ve şarj kayıtlarınız, masraf bölüşmeleriniz ve ayarlarınız cihazınızda saklanır.
- Son hesapladığınız rotanın özeti (başlangıç ve varış adı, tutarlar, rota bağlantısı) ana ekran widget'ında gösterilmek için yalnız bu cihazda tutulur; iCloud'a eşitlenmez. Yeni bir rota hesaplayınca üzerine yazılır, uygulamayı silince silinir.
- iCloud'a girişliyseniz bu veriler cihazlarınız arasında eşitlenmek için kendi iCloud hesabınızın **özel** veritabanında tutulur. Bu veritabanına yalnızca siz erişebilirsiniz; geliştirici erişemez. Verileri silmek için uygulamadaki kaydı silmeniz ya da Ayarlar › [adınız] › iCloud'dan uygulamanın verisini silmeniz yeterlidir.

## Ortak yolculuk

Bir masraf bölüşmesi için "Ortak yolculuk başlat"a dokunursanız bölüşme (yolculuk adı, rota bağlantısı, kişi adları, kalemler, tutarlar ve ödemeler) iCloud paylaşımıyla paylaşılır. Katılma bağlantısına sahip olan ve bağlantıyı iCloud hesabıyla açan herkes bölüşmeyi görüp düzenleyebilir. Bağlantıyı yalnızca yolculuktakilerle paylaşın. Paylaşımı istediğiniz zaman durdurabilirsiniz; katılımcılar da istedikleri zaman ayrılabilir.

## Üçüncü taraflara giden istekler

Uygulama hesaplama için şu hizmetlere istek gönderir. Bu isteklerde kimliğinizi belirten bir bilgi yoktur:

- **Apple Haritalar (MapKit):** Rota, yer arama ve adres bilgisi. Apple'ın gizlilik politikası geçerlidir.
- **Apple Hava Durumu (WeatherKit):** Elektrikli araçta soğuk havanın tüketime etkisini hesaplamak için rotanın başlangıç ve varış noktasının koordinatları ile çıkış ve varış saati, tahmini sıcaklığı almak üzere Apple'a gönderilir. Apple'ın gizlilik politikası geçerlidir.
- **EPDK:** Güncel akaryakıt fiyatları. İl fiyatı istendiğinde yalnızca ilin plaka kodu gönderilir.
- **Apple iCloud (herkese açık veritabanı):** Güncel gişe tarifeleri indirilir; sizden hiçbir bilgi gönderilmez.
- **Apple Haritalar kısa bağlantıları:** Apple Haritalar'dan paylaştığınız kısa bağlantı, açılabilmesi için Apple'a sorulur.

## Çocuklar

Uygulama yaşa özel veri toplamaz ve herkes için uygundur.

## Değişiklikler ve iletişim

Bu politika değişirse güncel hali bu sayfada yayımlanır. Sorularınız için: https://github.com/emircanbakar/kaca-patlar-destek/issues

---

# Privacy Policy (English summary)

Kaça Patlar has no server, accounts, ads or analytics, and the developer collects no data. Location is used on device only (starting point, province fuel prices, and the Live Activity after you start a trip) and is never sent to the developer. Trip-tracking locations are not stored; a route started from your location keeps that start point (rounded to about 11 m) in the Last Route widget's on-device summary and in the route link of expense splits you save (on device and in your iCloud). Your vehicles, fuel logs and expense splits stay on your device and, if you use iCloud, in your private iCloud database, which only you can access. If you start a shared trip, anyone with the join link can view and edit that expense split through iCloud sharing. The app sends requests to Apple Maps, Apple Weather (start and destination coordinates and times, for the temperature forecast), EPDK (the province plate code only, for fuel prices) and a public iCloud database (toll tariffs). Contact: https://github.com/emircanbakar/kaca-patlar-destek/issues
