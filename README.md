# Bank-Network-Simulation-Using-Cisco-Packet-Tracer

 A bankası İstanbul, Ankara ve İzmir olmak üzere 3 farklı şehirde şube açmayı planlamaktadır. Her şehirdeki şubeler 3 kattan oluşmaktadır. Bunlar; 
- 1.Kat İnsan Kaynakları, Bütçe ve Muhasebe, İnsan Kaynakları ve Toplantı Odası.
- 2.Kat Pazarlama ve Satış,Hukuk, Destek Hizmetleri ve Toplantı Odası.
- 3.Kat Bilgi Teknolojileri Yönetim, Altyapı Yönetim, İç Kontrol ve Sunucu Odasından oluşmaktadır.

- İlgili birimlerin neredeyse tamamında ip telefon ve her katta 1 adet yazıcı bulunmaktadır.
- Toplantı odalarında 1 adet Acces Point ve İş bilgisayarları bulunmaktadır ve bunların kablosuz bir şekilde haberleştirilmesi beklenmektedir.
- Tüm şubelerde yedeklilik beklenmektedir, ağda herhangi bir problem oluşursa ağ trafiği yedek switch üzerinden akmalıdır.
- Biri ana ISP, diğeri yedek olacak şekilde 2 adet ISP yapılandırılması beklenmektedir.
- Tüm cihazların dinamik olarak ip alması ve diğer şubeler ile haberleşebilmesi beklenmektedir.
- Tüm şubelerde IIS,DNS,FTP ve MAIL server kurulması ve ilgili yapılandırılmaların yapılması beklenmektedir.
- Sadece İç Kontrol birimlerinin ilgili şubelerdeki switch ve multilayer switchlere uzaktan erişim yapabilmesi (SSH) ve FTP sunucusuna erişebilmesi beklenmektedir.
- Sadece Altyapı Yönetim birimlerinin diğer tüm cihazlara ping atabilmesi beklenmektedir.



--------------------------------------------------------------------------------------------------------------------------

- Şirket içi network haberleşmesi ve kolay yönetim için vlan yapılandırılması yapıldı.
- Multilayer Switchlere vtp server kuruldu ve kat switchleri client moda alınıp vlan bilgileri alındı.
- Yapılandırmada bina içerisinde oluşabilecek olası bir multilayer swtich çökmesi durumu göze alınarak 2 adet multilayer swtich kullanılıp yedeklemesi yapıldı.
- Bütün toplantı odalarına Access Point ve iş laptopları konumlandırıp yapılandırıldı.
- Printerlerın bağlantıları gerçekleştirilip statik ipleri verildi.
- Sunucu odalarında bulunan serverlara DHCP, IIS, DNS, FTP, MAIL rolleri kurulup konfigürasyonu gerçekleştirildi ve network üzerinde haberleşmesi sağlandı.
- DHCP server konfigürasyonu yapılıp şirket içi bütün cihazların dinamik ip alması sağlandı.
- Routerlar üzerinden şirketin diğer şehirlerdeki şubeleri ile iletişimi sağlandı.
- Uzaktan erişim için Multilayer Swtich ile kat swtichlerine ssh konfigürasyonu yapıldı.
- Şirket şubeleri arasındaki alt yapı bağlantısı statik route ile haberleştirildi.
- Şirket içi ve şubeler arası telefon görüşmeleri için ip telefon kurulumu yapıldı.
- Şirketin 2 adet ISP ile yedekli olucak şekilde statik ve dinamik olarak yönlendirmesi yapıldı.
