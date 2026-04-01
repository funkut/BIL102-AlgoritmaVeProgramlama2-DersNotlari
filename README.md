Vize Konuları ve Soru Dağılımı
-- NYP kavramları (Nesne kavramı, kapsülleme, sınıf içi ve sınıf dışı erişim, nesne başlatma) 
-- Yapıcı ve yıkıcı fonksiyonların kullanımı. Yapıcı fonksiyonun aşırı yüklenmesi
-- Fonksiyon ve Operatör Aşırı Yüklemesi 
  * Banka Hesabı Örneği
  * Oyun Motoru Örneği

Soru Dağılımları 

-- Temel nesne kavramlarından bosluk doldurma veya kısa soru-cevap şeklinde soru gelecek. Bu şekilde bir section olacak. 
-- Yapıcı fonksiyonların kullanımı, aşırı yüklemesi (Yani farklı imzalarla yapıcı fonk. tasarımı -> Top sınıfını hatırlayın!)
-- Fonksiyon aşırı yüklemesi (yapıcı fonksiyonlardan da bilmeniz gereken bir kavram) -> Banka uygulamasındaki farklı hesapların farklı ozelliklerinin olması gibi. Örneğin vadeli, vadesiz, yatırım hesaplaro farklı ozelliklerle başlatılması gerekir. 
-- Operator aşırı yüklemesi -> Yine Banka Hesabı Örneğinden gidelim. VARLIKLARIM alanını düşünün. Ordaki tüm varlıklarınız aslında farklı hesapların toplanması ile elde edilir. 
Hesap türünden bir şeyi toplamayı derleyici bilmez, bunu siz tanımlayacaksınız. Örneğin 
  temp.gelir = h1.gelir + h2.gelir;
  temp.gider = h1.gider + h2.gider; gibi...

Sorumlu oldugunuz operatorler : 
  Unary grubu:
  * değil (!),
  * minus (-) // cıkarma işlemi değil negatifini alan operator (koordinat sistemi ornegi gelsin aklınıza!)
  * ++ veya --
  Binary grubu:
  * Aritmetik operatörler :  +, -, *, /
  * Lojik Operatorler : <, >, <=, >=, ==, =!, ...

ostream (<<), istream (>>), ToString() ve diger fonksiyon aşırı yüklemelerinden sorumlu değilsiniz !!!!

SON DERSTE YAPTIGIMIZ ÖDÜLLÜ ÖRNEĞİN İÇERİĞİNİN TAMAMINDAN SORUMLUSUNUZ. ÇÜNKÜ O ÖRNEKTE YUKARDA BAHSETTİĞİMZİ TÜM KAVRAMLAR DETAYLI OLARAK KULLANILIYOR. ÖDEVİ EN DOĞRU ŞEKİLDE YAPANIN ZORLANMAYACAĞI BİR SINAV OLACAK. 

ŞİMDİDEN BAŞARILAR...

