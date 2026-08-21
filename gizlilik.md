# Minamo Gizlilik Politikası / Privacy Policy

**Sürüm / Version:** 1.2 · **Yürürlük / Effective:** 21 Ağustos 2026 / 21 August 2026
**İletişim / Contact:** destek@hb4.aleeas.com

[Türkçe](#türkçe) · [English](#english)

---

## Türkçe

### Özet

Minamo'nun sunucusu yok, hesap istemiyor ve internet izni bile yok. Verileriniz telefonunuzda
kalır. Telefondan çıkmasının yalnızca üç yolu vardır ve üçünü de siz başlatırsınız: Health
Connect, yedek dosyası ve telefon değiştirme.

Bu politika, Minamo (paket adı `com.hb4sri.minamo`) Android uygulaması için geçerlidir.

### Sorumlu

Minamo'yu bağımsız bir geliştirici olarak tek başıma yapıyorum; arkasında bir şirket yok.
Sorularınız ve talepleriniz için bana yazabilirsiniz: **destek@hb4.aleeas.com**

### Telefonunuzda ne saklanıyor

Uygulamanın sakladığı her şey telefonunuzun kendi uygulama alanındadır.

**İçme verileri:** her kaydın miktarı, zamanı, içecek türü, hidrasyon yüzdesi, ait olduğu yerel
gün ve o andaki saat dilimi farkı. Tanımladığınız bardaklar. Hedef geçmişiniz. Kapanmış günlerin
mühürlenmiş sonucu.

**Ayarlar:** günlük hedefiniz; verdiyseniz kilonuz, etkinlik düzeyiniz, iklim seçiminiz ve
biyolojik cinsiyetiniz; hatırlatıcı tercihleri ve sessiz saat aralığı; tema, renk, birim ve dil
tercihleri; seri, seviye ve kazanılmış rozetler.

**Saklanmayanlar:** adınız, e-posta adresiniz, telefon numaranız, konumunuz, cihaz kimliğiniz ve
reklam kimliğiniz. Bunların hiçbiri istenmez ve saklanmaz.

Kilo ve biyolojik cinsiyet sağlık verisidir. Yalnızca günlük hedef önerisini hesaplamak için
kullanılır ve Health Connect'e yazılmaz. Minamo bunları kendiliğinden hiçbir yere göndermez;
yalnızca siz yedek dosyası oluşturursanız o dosyaya girerler ve yeni telefona geçerken sistemin
cihazdan cihaza aktarımına dahil olurlar.

### Reklam, analitik ve izleme

Yoktur. Minamo'da reklam ağı, analitik, çökme telemetrisi ve çapraz uygulama izleme bulunmaz.
Reklam kimliğiniz okunmaz. Uygulamada üçüncü taraf bir veri toplama kütüphanesi paketlenmemiştir.

### İzinler

Uygulama `INTERNET` izni **istemez.** Bu izin olmadan uygulama kendi başına ağ üzerinden hiçbir
veri gönderemez.

İstenen izinler: hatırlatıcılar ve isteğe bağlı ilerleme bildirimi için `POST_NOTIFICATIONS`
(ikisi de kapalı gelir); Health Connect için `READ_HYDRATION` ve `WRITE_HYDRATION` (yalnızca
siz açarsanız). Ayrıca zamanlanmış işleri yürüten sistem
kütüphanesinin eklediği `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED`, `FOREGROUND_SERVICE` ve
`ACCESS_NETWORK_STATE` izinleri görünür; bir de uygulamanın kendi adıyla başlayan
`DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` vardır ve bunu Android destek kütüphanesi kendi
bileşenini başka uygulamalardan korumak için ekler. Bunların hiçbiri ağ erişimi vermez;
`ACCESS_NETWORK_STATE` yalnızca bağlantı durumunu sorgulamaya izin verir ve uygulama tarafından
kullanılmamaktadır.

### Sağlık verisi ve Health Connect

Health Connect'i siz açarsanız Minamo su verisi alışverişi yapar. Health Connect, telefonunuzda
çalışan bir sistem bileşenidir; Minamo'nun ya da başka bir şirketin sunucusu değildir.

**Yazma:** yalnızca su ve maden suyu kayıtları, gerçek mL değeriyle yazılır. Çay, kahve, süt,
meyve suyu, gazlı içecek ve alkol Minamo'da kalır ve başka uygulamalara su olarak geçmez.
Kilonuz, biyolojik cinsiyetiniz, hedefiniz, seriniz ve rozetleriniz hiçbir zaman yazılmaz.

**Okuma:** başka uygulamaların yazdığı su kayıtları okunur ve günlük toplamınıza katılır. Bu
kayıtlar değiştirilmez ve silinmez. Geriye dönük sağlık geçmişi izni bilerek istenmez; bu izin
olmadan sistem, izni ilk verdiğiniz andan 30 günden daha eski kayıtları hiçbir uygulamaya
açmaz. Bir okuma bu sınıra takılırsa Minamo yalnızca son 30 güne bakar ve daha eski günleri
sıfır saymak yerine bilinmeyen olarak bırakır.

Health Connect verisi reklam, pazarlama veya satış amacıyla kullanılmaz; kredi, sigorta ya da
istihdam kararlarında kullanılmaz. Verilen izni istediğiniz zaman Health Connect üzerinden geri
alabilirsiniz.

### Verinin telefondan çıkabileceği durumlar

Üçü de sizin açık eyleminizle başlar. Tek istisna şudur: Health Connect eşitlemesini
açtıysanız, yarıda kalmış bir yazma bir sonraki açılışta kendiliğinden tamamlanabilir. Bu yeni
bir iş değildir; sizin zaten istediğiniz işin bitirilmesidir.

**1. Health Connect.** Yukarıda açıklandığı gibi, yalnızca siz açarsanız.

**2. Yedek dosyası.** Siz seçerseniz verileriniz tek bir JSON dosyasına yazılır ve dosyanın nereye
kaydedileceğini sistemin dosya seçicisiyle siz belirlersiniz. **Dosya şifrelenmez;** kaydettiğiniz
yer (telefonunuz ya da seçerseniz bir bulut hizmeti) dosyayı okuyabilir. Uygulama bu uyarıyı dosya
seçici açılmadan önce gösterir.

**3. Telefon değiştirme.** Yeni bir telefona geçerken işletim sisteminin aktarım akışı Minamo'nun
veritabanını ve ayarlarını taşıyabilir. Bunu siz ve işletim sistemi başlatır. Android'in bulut
yedeği uygulamada kapalıdır, bu nedenle verileriniz Google Drive yedeğine dahil edilmez.

### Saklama süresi ve silme

Verileriniz siz silene ya da uygulamayı kaldırana kadar saklanır; süre sınırı yoktur.

Ayarlar içindeki **"Verilerimi sil"** telefondaki tüm uygulama verisini temizler. Silme sırasında
Health Connect'e yazılmış kayıtların da silinip silinmeyeceği ayrıca sorulur.

**Yalnızca telefondan silmeyi seçerseniz** Health Connect'teki kayıtlara dokunulmaz; onlar orada
kalır ve Health Connect üzerinden silinebilir.

Health Connect'ten de silinmesini istediğiniz hâlde izin o an kapalıysa, silinmesi gereken
kayıtların listesi telefonda geçici olarak tutulur. Bu liste yalnızca kayıt kimliklerini içerir,
içilen miktarı değil. İzin geri verildiğinde kayıtlar silinir ve liste boşalır; o ana kadar
uygulama silmeyi tamamlanmış gibi göstermez.

Uygulamayı kaldırmak telefondaki tüm Minamo verisini siler. Health Connect'e daha önce yazılmış
kayıtlar Health Connect'te kalır; kaldırılmış bir uygulama onları silemeyeceği için bu kayıtları
Health Connect üzerinden siz silersiniz.

**Yedek geri yüklemek de bir silmedir:** yedekte bulunmayan kayıtlar telefondan silinir ve Health
Connect'e yazılmış olanlar oradan da silinir.

Daha önce dışa aktardığınız yedek dosyaları sizin dosyalarınızdır; onları bulundukları yerden siz
silersiniz.

### Çocuklar

Uygulamanın günlük hedef önerisi yetişkinler (18 yaş ve üzeri) için hesaplanır. Uygulama çocuklara
yönelik değildir.

### Sağlık sorumluluk reddi

Minamo bir tıbbi cihaz değildir ve hiçbir tıbbi durumu teşhis, tedavi, iyileştirme veya önleme
amacı taşımaz. Günlük hedef, yalnızca içeceklerden gelen tahmini sıvı katkısıdır (yiyeceklerden
gelen su kapsam dışıdır) ve bir reçete değildir. Kalp, böbrek ya da başka bir nedenle sıvı
kısıtlamanız varsa hedefinizi doktorunuzun talimatına göre ayarlayın.

### Bu politikadaki değişiklikler

Politika değişirse bu sayfadaki sürüm numarası ve yürürlük tarihi güncellenir. Uygulamanın veri
davranışını değiştiren bir güncelleme yayımlanırsa politika aynı sürümde güncellenir.

### İletişim

**destek@hb4.aleeas.com**

---

## English

### Summary

Minamo has no server, no accounts, not even the internet permission. Your data stays on your
phone. There are only three ways it can leave, and you start all three: Health Connect, a backup
file, and switching phones.

This policy applies to the Minamo Android app (package `com.hb4sri.minamo`).

### Who is responsible

I make Minamo on my own, as an independent developer; there is no company behind it. For
questions and requests, you can write to me: **destek@hb4.aleeas.com**

### What is stored on your phone

Everything the app stores lives in your phone's own app storage.

**Drink data:** each record's amount, time, drink type, hydration percentage, the local day it
belongs to, and the time zone offset at that moment. The cups you set up. Your goal history. The
sealed result of closed days.

**Settings:** your daily goal; if you provided them, your weight, activity level, climate choice
and biological sex; reminder preferences and quiet hours; theme, colour, unit and language
preferences; your streak, level and earned badges.

**Not stored:** your name, email address, phone number, location, device ID or advertising ID.
None of these are requested or kept.

Weight and biological sex are health data. They are used only to calculate your suggested daily
goal and are never written to Health Connect. Minamo never transmits them on its own; they are
included in a backup file if you create one, and in the system's device-to-device transfer when
you move to a new phone.

### Ads, analytics and tracking

There are none. Minamo contains no ad network, no analytics, no crash telemetry and no cross-app
tracking. Your advertising ID is not read. No third-party data collection library is bundled in
the app.

### Permissions

The app does **not** request the `INTERNET` permission. Without it, the app cannot send any data
over the network on its own.

Requested permissions: `POST_NOTIFICATIONS` for reminders and the optional progress notification
(both start out off); `READ_HYDRATION` and `WRITE_HYDRATION` for Health Connect (only if you turn
it on). In addition, the system library that runs scheduled
work adds `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED`, `FOREGROUND_SERVICE` and `ACCESS_NETWORK_STATE`;
there is also `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`, prefixed with the app's own id, which
the Android support library adds to keep its own component private to the app.
None of these grant network access; `ACCESS_NETWORK_STATE` only allows querying connectivity
status and is not used by the app.

### Health data and Health Connect

If you turn Health Connect on, Minamo exchanges hydration data with it. Health Connect is a system
component running on your phone; it is not a server operated by Minamo or any other company.

**Writing:** only water and mineral water records are written, at their real mL value. Tea,
coffee, milk, juice, soda and alcohol stay in Minamo and are never passed to other apps as water.
Your weight, biological sex, goal, streak and badges are never written.

**Reading:** hydration records written by other apps are read and added to your daily total. Those
records are never modified or deleted. The historical health data permission is deliberately not
requested; without it, the system never exposes records older than 30 days before the moment you
first granted the permission. If a read runs into that limit, Minamo narrows to the last 30 days
and treats older days as unknown rather than zero.

Health Connect data is never used for advertising, marketing or sale, and never for credit,
insurance or employment decisions. You can revoke the permission at any time through Health
Connect.

### When data can leave your phone

All three begin with an explicit action by you. There is one exception: if you have turned on
Health Connect sync, a write that was interrupted can complete on its own the next time the app
opens. That is not new work; it is finishing work you already asked for.

**1. Health Connect.** As described above, only if you turn it on.

**2. Backup file.** If you choose to export, your data is written to a single JSON file and you
pick where it is saved using the system file picker. **The file is not encrypted;** wherever you
save it (your phone, or a cloud service if you choose one) can read it. The app shows this warning
before the file picker opens.

**3. Switching phones.** When you move to a new phone, the operating system's transfer flow can
carry Minamo's database and settings. You and the operating system start this. Android's cloud
backup is disabled for this app, so your data is not included in a Google Drive backup.

### Retention and deletion

Your data is kept until you delete it or uninstall the app. There is no time limit.

**"Delete my data"** in Settings clears all app data on the phone. During deletion you are asked
separately whether records written to Health Connect should be removed as well.

**If you choose to delete only from the phone,** the records in Health Connect are left untouched;
they stay there and can be deleted through Health Connect.

If you do ask for them to be removed but the permission is off at that moment, the list of records
still to be deleted is kept on the phone temporarily. That list contains only record identifiers,
not the amounts you drank. Once the permission is granted again the records are deleted and the
list empties; until then the app does not present the deletion as completed.

Uninstalling the app removes all Minamo data from the phone. Records previously written to Health
Connect remain in Health Connect; an uninstalled app cannot delete them, so you remove those
records through Health Connect yourself.

**Restoring a backup is also a deletion:** records not present in the backup are removed from the
phone, and from Health Connect as well if they had been written there.

Backup files you exported earlier are your own files; you delete those from wherever you saved
them.

### Children

The app's daily goal suggestion is calculated for adults (18 and over). The app is not directed at
children.

### Health disclaimer

Minamo is not a medical device and is not intended to diagnose, treat, cure or prevent any medical
condition. The daily goal is only an estimate of fluid from beverages (water from food is out of
scope) and is not a prescription. If you have a fluid restriction for heart, kidney or other
reasons, set your goal according to your doctor's instructions.

### Changes to this policy

If this policy changes, the version number and effective date on this page are updated. If an app
update changes data behaviour, the policy is updated in the same release.

### Contact

**destek@hb4.aleeas.com**
