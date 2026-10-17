

https://github.com/user-attachments/assets/4a4c8384-aaa1-4062-90f7-2247b1bf9663



https://github.com/user-attachments/assets/30716bc3-3f35-46f4-a0e3-338fd4c422e7



https://github.com/user-attachments/assets/b3531c32-ba97-41c9-ad2d-99c7169ce4d7

Robodog-Byte

Bu depo, 6 eksenli gyro-ivme sensörü ve ters kinematik altyapısıyla geliştirilmiş Robodog-Byte projesine aittir.

Proje Görselleri ve Videoları

Aşağıdaki bağlantılardan robotun çalışma anına ait videolara ulaşabilirsiniz:

[Video 1](https://github.com/user-attachments/assets/6903bfb2-41f7-4e26-8655-ac19dc173aee)
[
Video 2](https://github.com/user-attachments/assets/7fca8d4d-c983-4fee-9f00-6a704615e3ec)

Kod İçerisinde Kullanılan Temel Mekanikler ve Fonksiyonlar

1. motor_set (Sınıf)

Motorların pin bilgilerini tutar.

Her bir motor için kalibrasyon noktalarını tanımlar ve saklar.

2. Dinamik()

6 eksenli gyro-ivme sensöründen anlık verileri alır.

Robotun eğim değişimlerinde dengesini sağlayarak gövdesini her zaman düz tutmasına yardımcı olur.

3. swrite()

Motorlara gönderilecek PWM sinyallerini işler.

Açı verilerini PWM sinyallerine dönüştürerek daha okunaklı ve yönetilebilir bir kod yapısı sağlar.

4. pos_cal()

Robotun tüm bacaklarını kalibrasyon amacıyla sıfır (başlangıç) konumlarına getirir.

5. kinematik()

Her bacağın hedef konumunu koordinat olarak alır.

Gitmesi gereken konum için Femur, Tibia ve Coxa açılarını hesaplar.

Manuel açı verisi girmeye gerek kalmadan, ayak uçlarını istenilen koordinatlara otomatik olarak taşır.

https://github.com/user-attachments/assets/6903bfb2-41f7-4e26-8655-ac19dc173aee





