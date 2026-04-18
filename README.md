# Mini Katalog Uygulaması

Bu proje, Flutter kullanılarak geliştirilen mini katalog uygulamasıdır. Uygulamada ürünler JSON dosyasından okunur, asset klasöründeki görseller ile birlikte GridView yapısında listelenir. Kullanıcı ürün detaylarını görebilir, ürünleri sepete ekleyebilir, sepet ekranında ürün adedini artırıp azaltabilir ve toplam tutarı görüntüleyebilir.

## Proje Özellikleri

- JSON dosyasından ürün verisi okuma
- Asset klasöründen görsel kullanımı
- GridView ile ürün listeleme
- Ürün detay sayfası
- Navigator ile sayfa geçişi ve veri taşıma
- Sepete ürün ekleme
- Sepette ürün adedi artırma ve azaltma
- Sepetten ürün silme
- Toplam tutar hesaplama
- Ürün arama özelliği

## Kullanılan Teknolojiler

- Flutter
- Dart
- Material Design
- JSON
- Asset management

## Flutter Sürümü

Flutter stable sürümü kullanılmıştır.

## Projeyi Çalıştırma Adımları

1. Flutter SDK kurulu olmalıdır.
2. Proje klasörü açılır.
3. Terminalde `flutter pub get` komutu çalıştırılır.
4. Telefon veya emulator bağlanır.
5. `flutter run` komutu ile uygulama başlatılır.

## Klasör Yapısı

- `lib/main.dart` → uygulamanın ana kodu
- `assets/products.json` → ürün verileri
- `assets/images/` → ürün görselleri

## Uygulama Ekranları

- Ana sayfa
- Ürün detay sayfası
- Sepet sayfası