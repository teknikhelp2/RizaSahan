TICKET
Her talep. Net bir takip.
Kurum içi destek taleplerini kaydetmek, ilgili ekibe atamak ve çözüm sürecini takip etmek için hazırlanmış, kendi sunucunuzda çalışan talep yönetim uygulaması.
=============================================================================================================================================================
Neler yapabilirsiniz?
-Talep açma, teknisyene atama, durum ve çözüm takibi
-Kullanıcı, grup ve kategori bazlı yetkilendirme
-Gelen e-postaları inceleyerek ticket’e dönüştürme
-Filtreli raporlar, Excel ve PDF çıktıları
-SLA takibi, otomatik görevler, projeler ve KPI
-Şirket logosu, portal başlığı, açık/koyu tema ve kişisel görünüm
-Tam proje yedeği alma ve yedekten geri dönme

Gereksinimler
=============================================================================================================================================================
Windows Server 2022 veya 2025, IIS ve .NET Framework 4.8 veya üstü. Kurulum yönetici hesabıyla çalıştırılır; gerekli IIS bileşenleri otomatik hazırlanır. Veritabanı MDB’dir, ayrıca SQL Server gerekmez.
Ayrıntılı gereksinimler ve sistem yöneticisinin hazırlayacağı işler BASLA.html içindedir.

Kurulum
=============================================================================================================================================================
Kurulum paketini C:\TICKET_KURULUM klasörüne çıkarın.
1-KURULUMU-BASLAT.bat dosyasını yönetici olarak çalıştırın.
http://localhost/TICKET/ adresini açın.
admin / admin ile giriş yapıp parolayı değiştirin.
Uygulama Default Web Site → TICKET, TICKET havuzu ve 80 portuyla kurulur. Mevcut IIS bileşenleri tekrar kurulmaz.
Boş pakette eski şirket, logo, kullanıcı veya ticket verileri bulunmaz. Kendi şirketinizi ve destek yapınızı tanımlayarak başlayabilirsiniz.
Yedekten dönüş
Temiz kurulumdan sonra eski tam klasör/ZIP yedeğini C:\TICKET_KURULUM\YEDEKLER içine koyup 2-YEDEKTEN-DON.bat dosyasını yönetici olarak çalıştırın. Yedekteki kullanıcı bilgilerinizle giriş yapın.
Dönüş sonrası mail ve otomasyon duraklatılır. Ayarları kontrol ettikten sonra 3-OTOMASYONU-AC.bat ile açabilirsiniz. Test ortamında kapalı bırakın. Yalnız MDB yedeği, ek dosyaları ve resimleri içermez.

Kılavuz
=============================================================================================================================================================
Paketi indirdikten sonra BASLA.html dosyasını tarayıcıda açın. Kurulum, kullanım, parametreler ve geri dönüş adımları burada anlatılır.
Canlı veritabanınızı, yedeklerinizi ve gizli bağlantı bilgilerinizi GitHub’a yüklemeyin.
