# Rent-A-Car-Project


Swingle Rent A Car, kullanıcıların araç kiralama işlemlerini kolayca gerçekleştirebileceği bir Java Swing uygulamasıdır. Uygulama, araç modelleri, benzin tipi, yaş, kiralama tarihleri gibi çeşitli özellikler sunar.

## İçindekiler

- [Özellikler](#özellikler)
- [Ekran Görüntüleri](#ekran-görüntüleri)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)

## Özellikler

- **Araç Modelleri**: Kullanıcılar farklı araç modellerini görüntüleyebilir ve seçim yapabilir.
- **Benzin Tipi**: Araçların benzin tipi (benzin, dizel, elektrikli, hibrit) bilgilerini içerir.
- **Araç Yaşı**: Araçların yaş bilgisi (yeni, 1-3 yaş, 3-5 yaş, 5+ yaş) mevcuttur.
- **Kiralama Tarihleri**: Kullanıcılar kiralama başlangıç ve bitiş tarihlerini seçebilirler.
- **Kullanıcı Dostu Arayüz**: Basit ve anlaşılır bir arayüz ile kullanıcı deneyimi ön planda tutulmuştur.

## Ekran Görüntüleri

![Araç Seçimi](https://github.com/wvazabi/Rent-A-Car-Project/blob/main/Images/car.png)
![Kiralama Detayları]([screenshots/rental_details.png](https://github.com/wvazabi/Rent-A-Car-Project/blob/main/Images/newbook.png))

## Kurulum

1. **Depoyu Klonlayın**
    ```sh
    git clone https://github.com/kullaniciadi/swingle-rent-a-car.git
    cd swingle-rent-a-car
    ```

2. **Gereksinimleri Kurun**
    - Java Development Kit (JDK) 8 veya üzeri

3. **Projeyi Derleyin ve Çalıştırın**
    ```sh
    javac -d bin src/com/swingle/*.java
    java -cp bin com.swingle.Main
    ```

## Kullanım

1. Uygulamayı başlattıktan sonra, ana ekrandan istediğiniz aracı seçin.
2. Araç detaylarını görüntüleyin ve kiralama tarihlerini girin.
3. Kiralama işlemini tamamlamak için gerekli bilgileri doldurun ve onaylayın.


