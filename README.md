# Veritabanı Sistemleri Projesi

# Proje Detayları

Bu proje, bir e-ticaret sitesinin veritabanı yapısını ve işleyişini detaylı bir şekilde ele almaktadır. Proje, kullanıcıların ürünleri görüntüleyebileceği detaylı bilgilerine erişebileceği, sepete ekleyebileceği ve çevrimiçi bir şekide satın alma işlemlerini gerçekleştirebileceği bir platformu hedeflemektedir. Ayrıca son derece güvenlikli satın alma,kayıt olma ve giriş yapma imkanı sunar. 

# Teknolojiler

Proje, Db SQLite veritabanı yönetim sistemi ve Python programlama dili kullanılarak geliştirilmiştir. Bu teknolojiler, projenin gereksinimlerini karşılamak üzere seçilmiştir. Ayrıca projemizde ön yüz tasarımı için HTML, CSS gibi arayüz tasarlamak için işaretleme dillerini kullandık. Veritabanını dizayn ederken görsel veri desteği sunan DbVisualiser teknolojisini kullandık. 

### Kullanıcı Kayıt Sistemi

E-Ticaret sitemizde kullanıcı kayıt ve girişleri için SMTP internet protokolünü kullandık. Bu teknoloji ile yeni kullanıcılarımıza e-mail aracılığı ile bir doğrulama sistemini ekledik. Bu sistem sayesinde hem veritabanımızda kullanıcının e-mail adresi kaydolacak ve aynı zamanda tekrar aynı e-mail adresi ile kayıt olamama özelliği ile kullanıcı güvenliğini üst düzeye çıkardık.

### Ödeme Sistemi Entegrasyonu

E-Ticaret sitemizde kullanıcı dostu ödeme sistemleri ekledik. Başlıca Stripe ve PayPal teknolojilerini entegre ettik. Bu teknolojiler sayesinde müşterilerin internet üzerinden güvenli bir şekilde ödemelerini yapmalarını amaçladık. Bundan dolayı, her ödeme sisteminde 3D Secure özelliğini zorunlu kıldık. Stripe teknolojisi sayesinde müşterilerin diledikleri gibi MasterCard, VISA veya AmericanExpress çipli kredi/banka kartlarını ödeme yöntemi olarak sunduk. İlerideki zamanlarda ödeme yöntemlerine kripto para ve Apple/Google Pay gibi sistemleri entegre etmeyi hedefliyoruz.
