Aşağıdaki özellikleri içeren bir web tabanlı randevu sistemi geliştirmek istiyorum. Lütfen bu proje için kullanıcı arayüzü, veritabanı yapısı ve backend akışlarını kapsayan detaylı bir çözüm önerisi sun ve örnek kodlarla birlikte ilerleyelim:

📌 Proje Özeti:
Kullanıcılar, bulundukları konuma yakın yerel berberleri görebilecek, içlerinden istediklerini seçip randevu oluşturabilecekler. Randevu oluşturulduğunda ilgili berbere bilgilendirme e-postası gidecek. Kullanıcılar randevularını en geç 1 saat kala iptal edebilecekler.

🔧 Temel Özellikler:

Yerel berberlerin listelenmesi (isim, adres, hizmetler, müsaitlik vs.)

Kullanıcının berber seçip randevu alabilmesi

Randevu alındığında berbere e-posta gönderilmesi

Kullanıcının randevusunu yalnızca randevudan 1 saat öncesine kadar iptal edebilmesi

📚 Teknik Gereksinimler:

Frontend: HTML/CSS + React.js önerilebilir

Backend: Node.js / Express veya Python / Django

Veritabanı: PostgreSQL veya MongoDB

E-posta gönderimi: SMTP (nodemailer gibi)

Lokasyon tabanlı sıralama önerileri (isteğe bağlı)

🗂 Veritabanı Önerisi:
Tablo yapıları (örnek):

Users: id, name, email, password

Barbers: id, name, address, email, services

Appointments: id, user_id, barber_id, datetime, status

⏱ İş Kuralları:

Aynı berber için çakışan randevular alınmamalı

Randevudan 1 saat önceye kadar kullanıcı iptal edebilir

E-posta ile randevu bildirimi berbere gitmeli (kısa mesaj ek opsiyon olabilir)

🎯 Claude’dan Beklentim:

Bu iş kurallarına göre adım adım proje mimarisi oluştur

Her bileşen için önerilen teknoloji yığını

Basit bir REST API taslağı

Örnek veri modelleri

Temel frontend akışı (sayfa yapısı)

Örnek e-posta gönderim kodu

Ayrıca proje ilerledikçe Claude’a şu görevleri de vereceğim:

Kod parçaları yazdırmak

Hataları düzeltmek

Unit test önerileri

Deployment planı (örneğin Vercel + Railway veya alternatifler)
backend php
frontend next.js
yapılanları githuba yükle
