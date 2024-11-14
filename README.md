# Yapay-Zeka-Projesi
## Yazılım Geliştirme Lab. dersi için google üzerinden görsel veri çekme kodları

**Proje Özeti:**
   Projemizde öncelikle ilgili yerlerden istenilen verileri çekmemize yarayan kodları yazdık. Python dilini kullandık. İlk yazdığımız kod bloğu ilgili anahtar kelimeyi 'Google Search'de taratarak görselleri indirmeye yarıyor.
   Söz konusu olan kod bloğu görseli:
![veri çekme kısmı](https://github.com/user-attachments/assets/6ec6718e-cc6d-4f93-b9c9-788a116c0888)

İlgili kodu kullanarak seçtiğimiz anahtar kelimelerle 15.000 adet civarında görsel indirdik. İndirilen verileri düzenledik, temizledik ve gerekli veri işleme adımlarını uyguladık.
Elimizde olan temizlenmiş verileri tekrardan bir python kodu yazarak veri arttırma işlemi uyguladık.
  Söz konusu olan kod bloğu görseli (2):
![veri işleme ve arttırma](https://github.com/user-attachments/assets/49fa1371-a7b5-4655-ad9a-b709d2f07af6)
Görseldeki kod bloğu seçilen verileri döndürme, filtreleme ve renk düzenleme işlemleri yapıyor.

**Kodların ve Programın Kullanımı**
  Veri sağlama için yazılan kod bloklarında 'query' etiketindeki boşluğa anahtar kelime girilmesi gerekmektedir. Kod çalıştırıldığında girilen anahtar kelimeyi yeni bir sekme açıp 'Google Search' arama çubuğuna yapıştırarak kaynak sayfasındaki ''img'' etiketlerinin url adreslerine erişiyor. Erişilen url adreslerindeki görsellerin hedef belirtilen sayıya kadar hepsini indiriyor. Görüntü ve erişim kolaylığı için 2 saniyelik kaydırma işlemleri yapıyor. Sayfanın sonuna gelindiğinde ise indirilen dosyaların yer aldığı klasörün yolunu bir mesaj şeklinde yazdırarak sekmeyi kapatıyor. Bu şekilde işlem tamamlanmış oluyor.

  Veri işleme ve arttırma için yazılan kod bloklarında ise tanımlanmış input ve output klasörlerine ihtiyaç duyuyor. Input klasörünün yolunu kodu çalıştırmadan önce belirtiyoruz ve bu klasördeki görselleri kod bloklarında belirtilen şekilde işleme ve seçilen sayıda arttırma işlemleri uyguluyor. Eğer bir çıkış klasörü varsa bu belirtiliyor, yoksa yazılan kod bölümü sayesinde otomatik olarak çıkış klasörü oluşturuyor. İşlenmiş görselleri bu klasöre kaydederek işlemi tamamlıyor.
