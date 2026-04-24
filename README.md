# YÖK Atlas API Verileri

Bu depo, YÖK Atlas sistemi üzerinden derlenen çeşitli üniversite bölümlerine ait istatistiksel verileri JSON formatında sunmaktadır.

## 📂 Veri Seti İçeriği

Proje içerisinde anlık olarak aşağıdaki mühendislik bölümlerine ait veriler yer almaktadır:
* **`ceng.json`**: Bilgisayar Mühendisliği bölümüne ait veriler.
* **`eee.json`**: Elektrik-Elektronik Mühendisliği bölümüne ait veriler.
* **`software.json`**: Yazılım Mühendisliği bölümüne ait veriler.

## 📊 Veri Yapısı (JSON Formatı)

Her bir dosya, ilgili bölümdeki üniversite programlarının detaylı istatistiklerini içeren JSON nesnelerinden (array) oluşur. İçerikte bulunan temel veri alanları şunlardır:
* **`program_kodu`**: YÖK program kodu.
* **`universite_adi`** ve **`fakulte`**: Üniversite ve fakülte ismi.
* **`dil`** ve **`burs_durumu`**: Eğitim dili ve burs durumu bilgisi.
* **`sehir`** ve **`sehir_nufusu`**: Şehir ve şehrin güncel nüfus bilgisi.
* **`universite_turu`**: Vakıf veya Devlet üniversitesi bilgisi.
* **`kontenjan`** ve **`akademisyen_sayisi`**: Bölüm kontenjanı ve bölümdeki toplam akademisyen sayısı.
* **`siralamalar`** ve **`puanlar`**: Yıllara göre (örneğin 2022, 2023, 2024 ve 2025) taban puan ve başarı sıralamaları.
* **`kayitli_ogrenci`**: Yıllara göre bölüme kayıtlı olan öğrenci sayıları.
* **`aday_bolum_tercihleri`** ve **`yerlesen_tercihleri`**: Adayların ve programa yerleşen öğrencilerin tercih istatistikleri (birinci tercih sayısı, ilk üç tercih sayısı ve ortalama tercih sırası vb.).

## 🚀 Kullanım
Bu depodaki JSON dosyalarını projelerinizde doğrudan bir veri kaynağı olarak kullanabilirsiniz. Üniversite tercih robotları yapmak, eğitim üzerine istatistiksel analizler veya veri bilimi projeleri geliştirmek için uygun bir altyapı sağlar.
