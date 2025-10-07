Keylogger Uygulaması (Eğitim Amaçlı)
<img width="1918" height="1025" alt="image" src="https://github.com/user-attachments/assets/364a9cd8-7029-4c5f-a256-06d705046f99" />

video linki= https://youtu.be/H2wXIBVtsY4
Bu proje, C# Windows Forms kullanılarak hazırlanmış bir tuş kaydedici (keylogger) uygulamasıdır.
Programın testi için kullanılan video Zehra Kelahmetoğlu'nun rızasıyla çekilmiştir.
Tamamen eğitim ve etik kullanım amaçlıdır. Program, kullanıcıdan açık izin alındığında klavye girişlerini kaydedip e-posta ile gönderir.

🚀 Özellikler

Klavye girişlerini gerçek zamanlı olarak dinler.

50 karakterden sonra kaydedilen verileri e-posta olarak gönderir.

Gmail SMTP üzerinden güvenli mail gönderimi sağlar.

Kullanıcı bilgileri (app password) .env dosyasıyla gizlenir.

.gitignore sayesinde gizli bilgiler GitHub’a yüklenmez.

Program ctrl+shift+herhangi bir tuş kombinasyonu ile projeyi istediğiniz zaman sonlandırabilirsiniz.

⚙️ Kurulum
1. Gerekli Paketler

Proje çalışmadan önce aşağıdaki NuGet paketinin yüklü olduğundan emin olun:

Install-Package dotenv.net

2. .env Dosyası Oluşturma

Proje dizinine (örneğin bin/Debug/ veya proje kök klasörüne) bir .env dosyası oluşturun:

APP_PASSWORD=yourapppassword


📌 Not:
Gmail hesabınız için “Uygulama şifresi” oluşturmanız gerekir.
Bu şifreyi Gmail → Google Hesabı > Güvenlik > Uygulama Şifreleri kısmından alabilirsiniz.

3. .gitignore Dosyası

GitHub’a yüklerken gizli bilgilerin açığa çıkmaması için .gitignore dosyanıza şu satırları ekleyin:

# Ortam dosyaları
.env

# Derleme çıktıları
/bin/
/obj/
/*.exe
/*.dll
/*.pdb
/*.log
/log.txt

🖥️ Kullanım

Klavyeden girdiğiniz karakterler kaydedilir.

50 karakterden sonra otomatik olarak e-posta gönderilir.

E-posta gönderildikten sonra uygulamayı ctrl+shift+herhangi_bir_tuş ile kapatabilirsiniz.

🛡️ Etik Kullanım Uyarısı

Bu proje yalnızca eğitim amaçlıdır.
Herhangi bir kullanıcıdan izin alınmadan klavye verilerini kaydetmek veya paylaşmak yasal değildir.
Kodu kullanmadan önce karşı tarafın açık rızasını almanız gerekmektedir.

👩‍💻 Geliştirici

Elif Nur Günay
📧 elifgunay444@gmail.com

🎓 Yazılım Mühendisliği 2. Sınıf 
