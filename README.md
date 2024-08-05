  <a href="https://www.php.net" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> 
    </a> 
    <br>
<h1>BTK Akademi PHP dersleri egzersizleri</h1>

![Ekran görüntüsü 2024-03-19 202016](https://github.com/arazumut/PHPdersleri/assets/150933483/4cdb59f3-7286-48a6-b075-0b0b2ce21330)
![Ekran görüntüsü 2024-03-19 201912](https://github.com/arazumut/PHPdersleri/assets/150933483/7a57bc66-e15b-4576-aca8-b9317dcb3d11)
![Ekran görüntüsü 2024-03-19 201940](https://github.com/arazumut/PHPdersleri/assets/150933483/fbdc2bdf-60c8-4f81-a191-c81dda99e398)
![Ekran görüntüsü 2024-03-19 201924](https://github.com/arazumut/PHPdersleri/assets/150933483/df1b0d3d-808b-4c7d-9b43-b3ea0d6def73)

<h1>Online Payment System</h1>

Giriş
Günümüzde dijital ticaretin hızla artmasıyla birlikte, çevrimiçi ödeme sistemlerine duyulan ihtiyaç da aynı oranda yükselmiştir. Çevrimiçi ödeme sistemleri, kullanıcıların internet üzerinden güvenli ve hızlı bir şekilde alışveriş yapmalarını sağlar. Bu makalede, PHP kullanılarak tasarlanmış basit bir ödeme sistemi ele alınacaktır. Bu sistem, kullanıcıların kredi kartı bilgilerini girerek ödeme yapmalarına olanak tanıyan temel bir yapıya sahiptir ve Stripe ödeme sağlayıcısı entegrasyonu ile çalışmaktadır.

Projenin Amacı

Bu projenin temel amacı, PHP ile çevrimiçi bir ödeme sistemi oluşturmak ve Stripe API'si aracılığıyla ödeme işlemlerini güvenli bir şekilde gerçekleştirmektir. Bu sistem, kullanıcı dostu bir arayüz sunarak ödeme işlemlerinin kolay ve hızlı bir şekilde yapılmasını sağlar. Ayrıca, ödeme sürecinin güvenliğini artırmak için Stripe'in sağladığı güvenlik önlemlerinden faydalanmaktadır.

Projenin Kapsamı
Proje, aşağıdaki bileşenlerden oluşmaktadır:

Kullanıcı Arayüzü: Kullanıcıların ödeme bilgilerini girebileceği bir form sunar.
Ödeme İşleme: Kullanıcı tarafından girilen ödeme bilgilerini alır ve Stripe API'si aracılığıyla ödemeyi gerçekleştirir.
Yapılandırma Dosyaları: Stripe API anahtarları ve diğer ayarların saklandığı yapılandırma dosyaları içerir.
Projenin Teknik Detayları
Yapılandırma Dosyası (config.php):

Bu dosya, Stripe API anahtarlarını içerir ve Stripe PHP SDK'sını yükler.
Stripe API'sine erişim sağlamak için gerekli olan gizli anahtar burada tanımlanır.
Ödeme Formu (index.php):

Kullanıcının kredi kartı bilgilerini girebileceği bir form sunar.
Stripe Elements kullanılarak kredi kartı bilgileri güvenli bir şekilde alınır.
Kullanıcı, ödeme formunu doldurduktan sonra bilgilerini gönderir.
Ödeme İşleme (charge.php):

Formdan alınan kredi kartı bilgilerini işleyerek Stripe API'sine gönderir.
Stripe API'si aracılığıyla ödeme işlemini gerçekleştirir ve sonucu kullanıcıya bildirir.
Ödeme işlemi başarılı olduğunda, kullanıcının e-posta adresine bir makbuz gönderilir.
Güvenlik ve Uygulama Detayları
Güvenli Ödeme İşlemleri: Kredi kartı bilgileri, Stripe Elements kullanılarak alınır ve doğrudan Stripe sunucularına gönderilir. Bu yöntem, hassas bilgilerin sunucumuzda saklanmasını veya işlenmesini önleyerek güvenliği artırır.
API Anahtarlarının Yönetimi: Stripe API anahtarları, config.php dosyasında saklanır ve bu anahtarların güvenliğini sağlamak için dosya izinleri uygun şekilde ayarlanır.
Hata Yönetimi: Ödeme işlemi sırasında oluşabilecek hatalar yakalanır ve kullanıcıya uygun şekilde bildirilir.
Sonuç
PHP ile tasarlanan bu basit ödeme sistemi, çevrimiçi ticaret siteleri için temel bir ödeme altyapısı sağlar. Stripe entegrasyonu sayesinde güvenli ve hızlı ödeme işlemleri gerçekleştirilir. Bu sistem, kullanıcıların kredi kartı bilgilerini güvenle girebileceği ve işlemlerini hızlı bir şekilde tamamlayabileceği bir çözüm sunar. Çevrimiçi ticaret yapan işletmeler için temel bir ihtiyaç olan ödeme sistemleri, bu proje ile kolaylıkla hayata geçirilebilir ve kullanıcı memnuniyeti artırılabilir.

![Ekran görüntüsü 2024-07-19 112226](https://github.com/user-attachments/assets/218b0e0e-368b-4fee-949d-7b184c1f0ada)


![Ekran görüntüsü 2024-07-19 093642](https://github.com/user-attachments/assets/6c00dd78-1d5a-499b-9abd-8c9eb29c13f3)

![Ekran görüntüsü 2024-07-19 093700](https://github.com/user-attachments/assets/21f3841b-8f52-45e3-913c-1caa16f6e362)
![Ekran görüntüsü 2024-07-19 093715](https://github.com/user-attachments/assets/7e007f04-f9f1-4827-a237-bbeb7f2685ab)
