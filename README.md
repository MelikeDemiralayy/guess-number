# Guess My Number 

Gues My Number JavaScript pratiği yapmak için geliştirdiğim bir sayı tahmin etme oyunudur.1 ile 20 arasındaki rastgele seçilen bir sayı tahmin edilir. Bu projede Java Script kullanılarak DOM manipülasyonları yapılır ve oyunun işleyişi dinamik hale getirilir.

## Özellikler
- Rastegele Sayı Üretme: Math random() fonksiyonu kullanılarak rastgele sayı üretilir.
- DOM manipülasyonları: JavaScript kullanılarak HTML elementlerine erişilir ve oyun sırasında kullanıcıya mesajlar verilir, stilde değişiklikler yapılır.
- Skor Takibi: Her yanlış tahminde skor bir azalır. Doğru tahminde yüksek skor güncellenir.
- Tekrat başlama: Oyun bittikten sonra again butonuna basılarak oyun sıfırlanabilir.

## Kurulum:
- Projenin yerel ortamda çalıştırılması için aşağıdaki adımları takip edebilirsiniz:

- Projeyi klonlayın ya da zip dosyası olarak indirin:
  ```bash
  git clone <repository-url>
  ```

 - Proje konumuna gidin:
  ```bash
   cd <project-directory>
```

- Herhangi bir tarayıcıda projeyi çalıştırın.

##  Proje Yapısı:
  ```bash
   guess-my-number/
├── index.html
├── style.css
└── script.js

```
- index.html: Oyunun HTML yapısını içerir. Başlık, butonlar, sayı girişi ve puan bilgileri bu dosyada yer alır.
- style.css: Oyunun stil içerikleri burada yer alır.
- script.js: Oyun mantığını ve etkileşimleri yöneten JavaScript dosyasıdır. DOM manipülasyonu, olay dinleyiciler ve oyunun ana fonksiyonları burada yer alır.
  
## JavaScript Fonksiyonları:

- openModal() ve closeModal(): Modal penceresini açıp kapatmak için kullanılan fonksiyonlar. Sınıf manipülasyonlarıyla DOM'a etki eder.
- displayMessage(message): Oyunun mesajlarını değiştirmek için kullanılır.document.querySelector() ile .message elementine erişip içerik değiştirir.

### Olay Dinleyiciler:
- check butonuna tıklanıldığında, oyuncunun girdiği tahmin işlenir ve oyun mantığı çalıştırılır.
- again butonuna basıldığında, oyun sıfırlanır ve baştan başlar.

## Katkıda Bulunma:
- Projeyi fork edin
- Yeni bir branch oluşturun (git checkout -b feature/ozellik).
- Değişiklikleri commit edin(git commit -m 'özellik ekle').
- Branch'e push edin (git push origin feature/ozellik).
- Bir pull request oluşturun. 
