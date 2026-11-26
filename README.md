# LGS Öğrenci Takip ve Deneme Hazırlama

8. sınıf LGS hazırlığı için öğrenci takibi, soru havuzu ve yazdırılabilir deneme kitapçığı hazırlama uygulaması.

## GitHub Pages'te yayınlama

GitHub Pages'in ana sayfayı otomatik açması için uygulama dosyasını depoda `index.html` adıyla bulundurun. Dosyanın adını değiştirmek istemiyorsanız sayfayı dosyanın adıyla biten URL'den açabilirsiniz:

```text
https://KULLANICI_ADI.github.io/DEPO_ADI/LGS_Ogrenci_Takip_Yazdirma_AltKonular.html
```

GitHub deposunda **Settings → Pages** bölümünden yayın kaynağını seçin. GitHub Pages adresi oluşunca uygulamayı bu adresten açın.

## Özellikler

- Ders ve alt konu ilerlemesini işaretleme ve ilerleme çubukları
- Haftalık ders programı, kaynak kitap ve deneme analizi takibi
- Çalışma süresi, soru sayısı, doğru, yanlış ve net kaydı
- Fotoğraf çekerek veya dosya yükleyerek soru havuzu oluşturma
- Sorulara isteğe bağlı doğru cevap ekleme ve yazdırılan kitapçığa cevap anahtarı koyma
- Deneme dizgisinde soruları sürükleyerek sıralama, genişletme, döndürme, kırpma, yakınlaştırma ve denemeden çıkarma
- Öğrenci verilerini JSON yedeği olarak dışa aktarma ve geri yükleme
- Öğretmen panelinde öğrenci yedeklerini açma ve öğrenciler arasında geçiş yapma

## Kullanım

1. Uygulamayı açın ve ortak giriş kodunu girin.
2. Öğrenci veya öğretmen görünümünü seçin.
3. Öğrenci görünümünde ad soyad ve hatırlatma yanıtıyla profil açın. Aynı tarayıcıda farklı öğrenciler için ayrı profiller kullanabilirsiniz.
4. Öğrenci kayıtlarını düzenli olarak **Öğrenci Yedeği İndir** ile yedekleyin.
5. Deneme hazırlamak için **Sorularım → Seçilen Sorulardan Deneme Oluştur** bölümünü açın. Dizgi ekranında soruları düzenleyip **Yazdır / PDF Kaydet** seçeneğine basın.

## Verilerin saklanması ve gizlilik

Uygulama sunucu kullanmaz. Öğrenci profilleri, çalışma kayıtları ve soru fotoğrafları uygulamanın açıldığı tarayıcıdaki IndexedDB alanında tutulur. Bu nedenle veriler başka bir cihaz veya tarayıcıya kendiliğinden eşitlenmez. Başka cihaza taşımak için JSON yedeğini kullanın.

Tarayıcı verilerini temizlemek, gizli pencere kullanmak veya cihazı değiştirmek kayıtların kaybolmasına neden olabilir. Yedek dosyalarını güvenli bir yerde saklayın; öğrenci bilgileri içeren yedekleri herkese açık GitHub deposuna yüklemeyin.

Ortak giriş kodu uygulamanın HTML/JavaScript dosyasının içindedir. Bu ekran yalnızca basit bir arayüz engelidir; gerçek kimlik doğrulama veya veri şifrelemesi sağlamaz. Gerçek erişim kontrolü ya da çevrimiçi eşitleme gerekiyorsa sunucu tarafında kimlik doğrulama ve erişim kuralları kurulmalıdır.

## Dosyalar

- `LGS_Ogrenci_Takip_Yazdirma_AltKonular.html` — uygulamanın tek dosyalık sürümü
- `README.md` — kullanım ve yayınlama bilgileri
