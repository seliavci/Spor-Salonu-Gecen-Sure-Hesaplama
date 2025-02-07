Proje Açıklaması: Bu C programı, kullanıcıdan spor salonuna giriş ve çıkış tarihleri ile saat bilgilerini alarak, bu tarihler arasındaki farkı hesaplar ve sonucu saat ve dakika olarak gösterir. 
Ayrıca, bu tarihler epoch zamanına dönüştürülür ve ekranda gösterilir. 
Bu program, günlük hayatın içinde spor salonunda geçirilen süreyi hesaplamak için kullanılabilir.

Kullanılan Bileşenler:
stdio.h: Giriş ve çıkış işlemleri için kullanılır.
time.h: Tarih ve saat hesaplamaları için kullanılır.
struct TarihSaat: Tarih ve saat bilgisini saklamak için özel olarak tanımlanmış bir yapı.

Nasıl Çalışır?
Kullanıcı Girişi: Program, kullanıcıdan spor salonuna giriş ve çıkış tarihlerini ve saatlerini alır.

Epoch Zamanı Dönüşümü: Kullanıcıdan alınan tarih ve saat bilgileri Unix Epoch zamanına dönüştürülür.

Zaman Farkı Hesaplama: Giriş ve çıkış zamanı arasındaki fark saniye cinsinden hesaplanır ve ardından saat, dakika cinsine çevrilir.

Sonuçlar: Spor salonunda geçirilen süre, saat ve dakika olarak hesaplanır ve epoch zamanları gösterilir.

Program çalıştırıldığında kullanıcıdan aşağıdaki gibi tarih ve saat bilgilerini girmesi istenir:
Spor salonuna giriş tarihini gir (YYYY MM DD HH MM SS): 2025 02 07 09 00 00
Spor salonundan çıkış tarihini gir (YYYY MM DD HH MM SS): 2025 02 07 10 30 00

Program ardından, belirtilen tarih ve saatler arasındaki farkı hesaplar ve epoch zamanını gösterir. Çıktı şu şekilde olabilir:
Spor salonunda geçirilen süre: 1 saat, 30 dakika
Giriş Zamanı (Epoch): 1738531800
Çıkış Zamanı (Epoch): 1738535400



Bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

Projeyi forklayın ve bilgisayarınıza indirin.
Yapmak istediğiniz değişiklikleri gerçekleştirin.
Değişikliklerinizi bir pull request ile gönderin.


Bu proje, MIT Lisansı ile lisanslanmıştır.

Bu açıklamalar, programınızın amacını, nasıl çalıştığını ve kullanıcıların nasıl faydalanabileceğini net bir şekilde belirtiyor. Eğer herhangi bir ekleme veya değişiklik yapmamı isterseniz, belirtebilirsiniz!
