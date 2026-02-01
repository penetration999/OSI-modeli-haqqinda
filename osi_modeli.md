#OSI Modelinin 7 Səviyyəsi
Məlumat ötürülərkən proses yuxarıdan aşağıya doğru, yəni Tətbiq (Application) qatından Fiziki (Physical) qata qədər davam edir.

 7. Tətbiq Qatı (Application Layer)
İstifadəçinin birbaşa şəbəkə ilə əlaqəyə keçdiyi qatdır. Proqramların şəbəkə xidmətlərindən istifadə etməsini təmin edir.

Protokollar: HTTP, HTTPS, POP3, SMTP, DNS.

 6. Təqdimat Qatı (Presentation Layer)
Məlumatı digər qatların başa düşəcəyi formata tərcümə edir. Məlumatın şifrələnməsi, deşifrə edilməsi və sıxılması burada baş verir.

Şifrələmə: SSL (köhnəlmiş şifrələmə bünövrəsi) və TLS (müasir və təhlükəsiz versiya).

Funksiyası: Məlumatın formatını (məsələn, JPEG, MP4, GIF) müəyyən edir.

 5. Sessiya Qatı (Session Layer)
Cihazlar arasında əlaqənin (sessiyanın) qurulmasını, idarə olunmasını və sonlandırılmasını təmin edir. Autentifikasiya (kimlik doğrulaması) və avtorizasiya (icazələrin yoxlanılması) burada baş verir.

Dialoq növləri:

Half-Duplex: Məlumat növbəli ötürülür (məsələn, ratsiya).

Full-Duplex: Eyni anda hər iki tərəf məlumat göndərə bilir (məsələn, telefon).

Protokollar: PAP (Sessiya açılarkən istifadəçini tanıyan sadə autentifikasiya protokolu).

 4. Nəqliyyat Qatı (Transport Layer)
Məlumatın haradan haraya və hansı qayda ilə gedəcəyini təyin edir. Burada "Source Port" (Mənbə portu) və "Destination Port" (Hədəf portu) əlavə olunur.

Ünvanlama Məntiqi: IP binanı, MAC mərtəbəni, Port isə otağı təmsil edir.

Əsas Protokollar:

TCP: Etibarlı və zəmanətli ötürmə. E-mail, fayl ötürülməsi (FTP) və veb-brauzerlərdə istifadə olunur. (Unicast: tək hədəfə).

UDP: Sürətli ötürmə. Canlı yayımlar, onlayn oyunlar və VoIP (səsli zənglər) üçün istifadə olunur. (Unicast, Multicast və ya Broadcast: hamıya).

 3. Şəbəkə Qatı (Network Layer)
Məlumat paketlərinin ən uyğun yolla (routing) hədəf IP ünvanına çatdırılmasını təmin edir.

Cihaz: Router (Yönləndirici).

Ünvanlama: IPv4 və IPv6.

Əlavə Protokollar: ICMP (Ping əmri üçün), IPSec (Paketlərin təhlükəsiz şifrələnməsi üçün).

 2. Məlumat Bağlantısı Qatı (Data Link Layer)
Məlumatın fiziki MAC ünvanları vasitəsilə bir cihazdan digərinə (eyni şəbəkə daxilində) ötürülməsini təmin edir.

Texnologiyalar: VLAN, WAN protokolları, Ethernet.

Vahid: Bu qatda məlumata "Kadr" (Frame) deyilir.

 1. Fiziki Qat (Physical Layer)
Yuxarı qatlardan gələn bütün məlumatlar burada "Bit"lərə (0 və 1) çevrilir. Məlumatın fiziki mühitlə (kabellər, radio dalğaları) elektrik siqnalları şəklində ötürülməsi bu qatda baş verir.
