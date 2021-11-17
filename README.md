# Gittigidiyor Test
> Java, Selenium ve Gherkin Syntax kullanılmıştır.
>
> Page object model prensiplerine bağlı, kolay güncellenebilir kod denemesi.
>
>Çalışma videosu: 

https://user-images.githubusercontent.com/37184598/142239118-1a83804b-c8da-4c32-a875-a92ff49e18bb.mp4


## Test Senaryosu

-Gittigidiyor anasayfasına giriş yap.

-Laptop araması yap. (İstediğin ürünü arayabilirsin.)

-İkinci sayfaya git. (İstediğin sayfaya gidebilirsin.)

-İkinci sayfada olduğunu kontrol et.

-Rastgele bir ürünü sepete ekle. (Ürünler liste halinde alınıyor. 0 ile ürün sayısı arasında sayı üreterek seçim yapıyor.)

-Sepete git.

-Ürün adetini iki yap. (İstediğin adeti seçebilirsin.)

-Ürün adetini iki olduğunu doğrula.

-Ürünü sepetten sil.

-Gittigidiyor anasayfasına geri dön.


## Sayfalar

**Home Page**

-*closeCookies* : Çerezler uyarısı kapatma

-*searchProduct* : Gönderilen parametreyi arar.

-*clickSearch* : Arama butonuna tıklar.


**Search Page**

-*validateResult* : Laptop araması yapma

-*goToPage* : Gönderilen parametredeki sayfaya gider.

-*validateSearchResult* : Gönderilen parametredeki sayfada olduğunu doğrular.

-*chooseProduct* : Sayfadaki ürünlerden rastgele bir ürün seçer.

-*addToCart* : Seçilen ürünü sepete ekler.

-*goToMyCart* : Sepetim sayfasına gider.


**Cart Page**

-*addAmount* : Gönderilen parametredeki değer mevcutsa o kadar ürün adeti seçer.

-*deleteProduct* : Sepetteki ürünü siler.

-*validateDelete* : Sepetteki ürünün silindiği doğrular.

-*goBackHome* : Anasayfaya geri döner.
