# Kutuphane-Sistemi
Online Library System


# Kütüphane Otomasyon Sistemi

:information_source: *Dersin Kodu:* [16303](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ16303/716026/tr)  
:information_source: *Dersin Adı:* [YAZILIM MİMARİSİ VE TASARIMI](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ16303/716026/tr)  
:information_source: *Dersin Öğretim Elemanı:* Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   

----------------------------------------------------------------------------------------------------------------------------------------------------------

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          	         | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1210505071 | Ramazan YERGÜN	      | Yazılım Mühendisliği     | PROJE_14      | [Github](https://github.com/Ramazanyergun)        |
| 1210505055 | Cemil YILDRIM        | Yazılım Mühendisliği     | PROJE_14      | [Github](https://github.com/cemilyildirim1)       |
| 1210505038 | Celal Kağan AĞMAN    | Yazılım Mühendisliği     | PROJE_14      | [Github](https://github.com/celalkaganagman)      |
| 1210505042 | Emirhan TANRIVERDİ   | Yazılım Mühendisliği     | PROJE_14      | [Github](https://github.com/EmirhanT121)          |

----------------------------------------------------------------------------------------------------------------------------------------------------------

## Proje Açıklaması


Yaptığımız kütüphane otomasyon sistemi; genel olarak MySQL veritabanını kullanarak kullanıcıların ve kitapların kaydını tutan ve kullanıcılarına teknolojik ortamda kitap ödünç alma imkanı sunan bir sistemdir. Geniş bir kitap veritabanını kullanıcıların hizmetine sunarak kitap takibini kolaylaştırıyor. Sistem ayrıca; kullanıcıların akıllı telefonları veya tabletleri üzerinden kütüphane hizmetlerine hızlı erişim sağlamak için mobil uyumlu bir arayüz sunar. Kütüphane yöneticileri, envanter takibi, raporlama ve kullanıcı yönetimi gibi işlemleri kolaylıkla gerçekleştirebilmektedirler.


----------------------------------------------------------------------------------------------------------------------------------------------------------

## Proje Dosya Yapısı

- */src*
  - */Abstract classes*
    - CommandAbstarct.java
    - Isim.java
  - */Classes*
    - AddBooksCommand.java
    - Admins.java
    - BarrowBooks.java
    - BarrowBooksDAO.java
    - Books.java
    - BooksDAO.java
    - BorrowBooksCommand.java
    - DbHelper.java
    - DbHelperSingleton.java
    - Ekleme.java
    - Guncelleme.java
    - JustName.java
    - ShowUsersCommand.java
    - Silme.java
    - UpdateBooksCommand.java
    - Users.java
    - UsersTableModel.java
    - YurutGenel.java
  - */Interfaces*
    - BaseDAO.java
    - IslemleriYurut.java
    - KitapIslemler.java
  - */ui*
    - AddBooks.form
    - AddBooks.java
    - adminPaneli.form
    - adminPaneli.java
    - girisEkranì.form
    - girisEkranì.java
    - kayìtEkranì.form
    - kayìtEkranì.java
    - kitapGuncelleme.form
    - kitapGuncelleme.java
    - kitapOduncAlma.form
    - kitapOduncAlma.java
    - kullanìcìEkranì.form
    - kullanìcìEkranì.java
    - kullanìcìKitaplarì.form
    - kullanìcìKitaplarì.java
    - oduncAlìnanKitaplar.form
    - oduncAlìnanKitaplar.java
    - ShowUsers.form
    - ShowUsers.java
- README.md 


----------------------------------------------------------------------------------------------------------------------------------------------------------

## Kurulum

Bilgisayarınıza MySQL ve java derleyicisi(önerilen NetBeans) uygulamalarını indirip kurun. Sonrasında sisteme yükledigimiz dosyaları bilgisayarınıza indirin.


----------------------------------------------------------------------------------------------------------------------------------------------------------

## Kullanım

1-Sisteme yüklediğimiz dosyaları indirin.(java dosyaları ve veritabanı scriptleri)
2-Uygulamaların giriş sayfasından başlatın.


----------------------------------------------------------------------------------------------------------------------------------------------------------

## Katkılar

https://www.btkakademi.gov.tr/portal/course/ileri-seviye-java-9353
https://www.youtube.com/watch?v=xoSscAyyRF0&list=PLqTxmV775eSlC8ikS5YBDPT3jsMvCBdZg
https://www.youtube.com/watch?v=5DOEhu7LwKg&list=PLLCTYkJ1vsDDoE7CJ_xfd373RKah1V0y9


----------------------------------------------------------------------------------------------------------------------------------------------------------

## İletişim

kagan2434@gmail.com
cemilyyildirim@gmail.com
yergunr@gmail.com
emirhantanriverdi284@gmail.com
