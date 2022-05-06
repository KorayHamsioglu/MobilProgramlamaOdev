# MobilProgramlamaOdev

Yıldız Teknik Üniversitesi Mobil Programlama Dersi 2. Ödevi (mp3 çalar uygulaması)

# Özellikler
1. Kullanıcı Giriş Ekranı \
-Şifre Kontrol, Hata Mesajları, Başarılı Giriş Mesajı \n
-3 defa yanlış bilgi girişinde kayıt sayfasına yönlendirme
2. Kayıt Ekranı
-Kullanıcı bilgileri alma (resim de dahil)
-Hata mesajları, veritabanı kontrolü
-Kayıt oluşturduktan sonra, kayıt için kullanılan mail adresine kullanıcı bilgileri gönderilir. (intent)
3. Menü Ekranı
-.mp3 uzantılı şarkıların listeleneceği media kısmına ve playlistlerin oluşturulacağı kısma yönlendirme.
4. Media ekranı
-External storage içerisindeki .mp3 dosyalarını isimlerine göre alfabetik olarak listeleme
-.mp3 dosyalarını mesajlaşma uygulamaları aracılığı ile paylaşma (intent)
-.mp3 dosyalarını telefondan ve recyclerView'dan silme (Android 11)
5. MediaPlayer Ekranı
-Şarkının çalması ve durdurulması için play, stop, pause butonları
-Seekbar üzerinde şarkının istenilen dakika:saniyesine gidebilme
-Şarkı ismi ve resminin aktivite üzerinde gösterilmesi
-Previous ve Next butonları ile telefondaki tüm şarkılar içinde gezinebilme (playlist seçilirse playlist içindeki şarkılar gezilebilir)
6. Playlistler Ekranı
-Oluşturulan playlistler isimleriyle berbaer listelenir
-Playlistler telefonda kalıcı olarak tutulup, silinebilir. (shared preferences)
7. Playlist Oluşturma Ekranı
-External storage içerisindeki seçilen .mp3 dosyalarını ekleyerek playlist oluşturma



# Bilgi


Uygulama içindeki dosya silme işlevi Android 11 sürümü için çalışmaktadır. createDeleteRequest methodu ile gerekli izin alınmıştır.
Veritabanı olarak Firebase Realtime Database kullanılmıştır ve ödev dökümanında istenen isim-şifre veritabanına tutulmuştur. Diğer bilgiler mail uygulamaları aracıyla kişinin mailine gönderilmiştir. 


Not: APK doyası release kısmındadır.
Not 2: Uygulama sadece telefon içerisindeki .mp3 uzantılı müzik dosyalarını listelemektedir.


# Görseller

<img width="440" alt="Ekran Resmi 2022-05-06 16 49 24" src="https://user-images.githubusercontent.com/87299676/167146169-2baac4fb-b3f4-49c9-befa-fc8e2409c486.png">

<img width="440" alt="Ekran Resmi 2022-05-06 16 50 42" src="https://user-images.githubusercontent.com/87299676/167146911-055ef9c5-c114-437f-9d0f-8145598074a1.png">

<img width="437" alt="Ekran Resmi 2022-05-06 16 53 01" src="https://user-images.githubusercontent.com/87299676/167146930-43cdbbf0-946f-4568-b049-6300e540559a.png">








