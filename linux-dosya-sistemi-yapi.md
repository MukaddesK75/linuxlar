🗂️ Linux (Pardus) Dosya Sistemi Nedir?
Pardus gibi Linux tabanlı işletim sistemlerinde her şey kök dizin ( / ) ile başlar.
 Yani klasörlerin en tepesinde / vardır ve her şey onun altına dallanır. Tıpkı bir ağaç gibi düşünebilirsin.



📁 /bin
Burası temel komutların (örneğin ls, cp, mv) durduğu yer. Yani sistem açıldığında çalışması gereken en temel araçlar burada.

📁 /boot
Bilgisayarın açılmasını sağlayan dosyalar burada. Pardus açılırken kullanılan çekirdek (vmlinuz) gibi önemli şeyler burada duruyor. Silersen sistem açılmaz, aman dikkatET :)

📁 /dev
Donanımların sanal temsilcileri burada. Mesela USB taktığında dev/sdb1 gibi bir şey oluşur. Gerçek bir cihaz değil ama işletim sistemi onunla bu klasör üzerinden iletişim kurar.

📁 /etc
Sistem ayar dosyaları burada. Mesela bir programın yapılandırma dosyası /etc/program.conf diye bir şey olabilir.

📁 /home
Her kullanıcıya özel klasörler burada yer alır. Mesela senin Pardus'taki kişisel dosyaların muhtemelen /home/kullanici-adin içindedir.
Konsolu ilk açtığında da bu dosyanın içinde olursun gennelikle

📁 /lib
Programların çalışması için gerekli olan kütüphaneler burada. Windows’taki .dll dosyalarının Linux versiyonları gibi düşünebilirsiniz.

📁 /mnt ve /media
Harici diskler, USB’ler genelde buraya bağlanır. Yani bir flaş bellek taktığında burada görebilirsin.

📁 /opt
Sonradan yüklenen bazı yazılımlar kendini buraya kurar. Özel programların evi diyebiliriz.

📁 /proc
Sistemin kalbi burada atıyor. Aslında burası fiziksel değil, sanal bir klasör. RAM üzerindeki sistem bilgilerini temsil ediyor.

*Sistem belleği hakkında bilgi olur (/proc/meminfo).

*İşlemci bilgisi olur (/proc/cpuinfo).

*Kernel(çekirdek) ayarları olur (/proc/sys)

📁 /root
Süper kullanıcı yani root hesabının evi. /home/root değil, direk /root içindedir.

📁 /sbin
Sistem yönetimi komutları burada. Genellikle root yetkisi isteyen komutlar bulunur.

📁 /tmp
Geçici dosyalar için. Yeniden başlattığında bu klasör temizlenir. Geçici takılmaların merkezi.

📁 /usr
Programlar, kütüphaneler, yardım dosyaları… çoğu burada. Çok geniş bir klasördür, içinde kendi içinde klasörler de vardır:

*/usr/bin → Komutlar

*/usr/lib → Kütüphaneler

*/usr/share → Ortak veriler

*/usr/local → Elle kurduğun programlar

📁 /var
Loglar, e-mail, cache gibi sık değişen dosyalar burada tutulur.
