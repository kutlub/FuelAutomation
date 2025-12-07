🚀 Özellikler
✅ Yakıt Türleri

Benzin (95)

Benzin (97)

Dizel

Euro Dizel

LPG

📦 Depo Yönetimi
![Uploading Ekran görüntüsü 2025-12-07 215544.png…]()

Depoya yakıt ekleme

Maksimum kapasite kontrolü (1000 litre)

Hatalı giriş kontrolü

Depo değerlerinin otomatik kaydedilmesi (depo.txt)

💰 Fiyat Güncelleme

Fiyatları yüzde (%) olarak artırma/azaltma

Fiyat dosyasına kaydetme (fiyat.txt)

Arayüzde otomatik biçimlendirilmiş gösterim

🛒 Satış Sistemi

Seçilen yakıt türüne göre yalnızca ilgili NumericUpDown aktif hale gelir

Kullanıcı miktarı belirler ve satış yapılır

Satış tutarı otomatik hesaplanır

Depodan düşme işlemi yapılır

Depo, fiyat ve progressbar değerleri güncellenir

📊 Arayüz Özellikleri

5 adet progressbar ile depodaki doluluk oranı

Tüm NumericUpDown kontrolleri otomatik maksimum değer alır

Decimal ve artış ayarları otomatik yapılır

📁 Proje Dosya Yapısı
FuelAutomation/
│── Form1.cs
│── Form1.Designer.cs
│── Program.cs
│── depo.txt
│── fiyat.txt
│── README.md

⚙️ Kullanılan Teknolojiler

C# .NET Framework

Windows Forms

Dosya okuma/yazma (System.IO)

ProgressBar, ComboBox, NumericUpDown kontrol yönetimi

📥 Kurulum

Projeyi GitHub’dan klonlayın:

git clone https://github.com/kullaniciadi/FuelAutomation.git


Visual Studio ile açın.

depo.txt ve fiyat.txt dosyalarının çalışma dizininde olduğundan emin olun.
Örnek içerikler:

depo.txt

500
600
750
400
300


fiyat.txt

38.50
40.20
39.10
40.80
22.45


Projeyi çalıştırın.

🎮 Kullanım
🔧 Depo Güncelleme

Değer gir → “Depo Güncelle”

Eğer değer 0’dan küçük veya toplam 1000’den büyükse otomatik Hata yazılır.

📈 Fiyat Güncelleme

Yüzdelik değer gir → “Fiyat Güncelle”

Örneğin %10 zam → 10

⛽ Satış

Yakıt türünü seç

İlgili NumericUpDown aktif olur

Miktarı gir

“Satış Yap” butonuna bas

Tutar hesaplanır ve depo güncellenir

🐞 Bilinen Hatalar / Notlar

“Euro Dizel” satış hesaplamasında yanlışlık varsa Form1.cs üzerinden düzeltilebilir.

Depo kapasiteleri sadece tam sayı olarak progressbar’a yansır.

📜 Lisans

Bu proje MIT lisansı ile paylaşılmıştır.
