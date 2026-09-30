# Tınaztepe Otomotiv Web Sitesi

İzmir'deki Tınaztepe Otomotiv galerisi için hazırlanmış tek sayfalık tanıtım sitesi. Tek bir `index.html` dosyasından oluşur; ek kurulum, sunucu veya derleme adımı gerekmez.

## Sayfa bölümleri

- **Açılış ekranı:** Logo, "Aracınızı satmak için İzmir'de en doğru adres" başlığı, Stoktaki araçlar / Hemen ara / WhatsApp'tan teklif al butonları ve Alım-Satım bilgi şeridi.
- **Galeriye uğrayın:** Adres, telefon, "Hemen ara" ve "Yol tarifi al" butonları, Google Haritalar'a giden harita görseli.
- **Instagram:** `@tinaztepeotomotiv` hesabına giden takip butonu.
- **Mobil çubuk:** Telefonda ekranın altında sabit duran "Hemen ara" ve "Teklif al" butonları.

## Mevcut bilgiler

| Bilgi | Değer |
| --- | --- |
| Telefon / WhatsApp | 0532 437 8464 |
| Adres | Tınaztepe Otomotiv, Beyazevler, 372 Sokak No:2/A, 35410 Gaziemir/İzmir |
| Stoktaki araçlar | https://tinaztepe.sahibinden.com/ |
| Instagram | https://www.instagram.com/tinaztepeotomotiv/ |
| Facebook | https://www.facebook.com/tinaztepeotomotiv |

## Bilgileri değiştirme

`index.html` dosyasını bir metin editörüyle açın ve "Bul ve değiştir" ile şunları güncelleyin:

- **Telefon numarası:** `905324378464` (WhatsApp ve arama bağlantıları), `+905324378464` (arama) ve `0532 437 8464` (ekranda görünen metin).
- **Adres:** `Tınaztepe Otomotiv, Beyazevler, 372 Sokak No:2/A, 35410 Gaziemir/İzmir, Türkiye` metni ve harita bağlantılarındaki kodlanmış hali (`T%C4%B1naztepe%20Otomotiv...`). Harita bağlantısını en kolay şekilde Google Haritalar'da yeni adresi aratıp Paylaş bölümündeki bağlantıyla değiştirebilirsiniz.
- **Linkler:** `tinaztepe.sahibinden.com`, `instagram.com/tinaztepeotomotiv` ve `facebook.com/tinaztepeotomotiv` ifadelerini arayın.
- **Açılış fotoğrafı:** Fotoğraf dosyanın içine gömülüdür. Değiştirmek için `<img class="bg" src="...">` satırındaki `src` değerini kendi dosyanızla (örneğin `img/kapak.jpg`) değiştirin ve görseli `index.html` ile aynı klasöre koyun.

## GitHub Pages ile yayına alma

1. GitHub'da yeni bir depo (repository) oluşturun.
2. `index.html` dosyasını depoya yükleyin.
3. Depoda **Settings > Pages** bölümüne girin.
4. **Source** olarak `Deploy from a branch`, dal olarak `main` ve klasör olarak `/ (root)` seçip kaydedin.
5. Birkaç dakika sonra site `https://kullanici-adi.github.io/depo-adi/` adresinde açılır.

Kendi alan adınızı bağlamak için aynı sayfadaki **Custom domain** alanını kullanabilirsiniz. Vercel veya Netlify'a da `index.html` dosyasını yükleyerek yayınlayabilirsiniz.

## Notlar

- Konum alanındaki harita bir çizimdir; tıklayınca Google Haritalar'da adres aranır. Canlı harita isterseniz Google Haritalar'da galeriyi bulup **Paylaş > Harita yerleştir** kodundaki `src` adresini bir `<iframe>` içinde kullanabilirsiniz.
- Yazı tipi (Jost) Google Fonts'tan yüklenir; internet yoksa sistem yazı tipine geçer.
- Instagram biyografisinde görünen adres (Buca) ile sitedeki adres (Gaziemir) farklıdır. Güncel olanı her iki yerde de aynı yapmanız önerilir.
