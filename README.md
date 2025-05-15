# 🛒 Ürün Fiyatı ve İndirim Hesaplayıcı – C# Konsol Uygulaması

Bu basit C# konsol uygulaması, kullanıcıdan ürün fiyatlarını alır, toplam fiyatı hesaplar ve bu toplam üzerinden %20 indirim uygular. Ayrıca kullanıcı tarafından belirlenen oranda da indirim uygulanabilir.

---

## 📌 Özellikler

- Kullanıcıdan 3 ürün fiyatı alır.
- Ürünlerin toplam fiyatını hesaplayıp ekrana yazdırır.
- Toplam fiyat üzerinden otomatik olarak %20 indirim uygular.
- Kullanıcının girdiği oran kadar da indirim uygulayabilme özelliği vardır.

---

## 🧩 Kullanılan Metotlar

### `double urunFiyatlari()`
- Kullanıcıdan 3 adet ürün fiyatı alır.
- Bu fiyatları toplayarak ekrana indirimsiz toplamı yazar.
- `return` ile toplam fiyatı döner.

### `void indirim(double indirim)`
- Parametre olarak gelen toplam fiyat üzerinden %20 indirim uygular.
- İndirimli fiyatı ekrana yazdırır.

### `void indirimVeTotal()`
- Kullanıcıdan toplam fiyat ve istenilen indirim oranını alır.
- Girilen oran kadar indirim yaparak sonucu ekrana yazar.

---

## ▶️ Kullanım

Kodun en altındaki kısım:

```csharp
double toplamfiyat = urunFiyatlari();
indirim(toplamfiyat);
indirimVeTotal();
