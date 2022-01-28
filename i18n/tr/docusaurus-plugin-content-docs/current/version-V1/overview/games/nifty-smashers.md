---
id: güzel parçalayıcılar
title: Şık Parçalayıcılar
sidebar_position: 2
---

  <div>
  <video width="100%" height="100%" playsInline controls loop>
  <source src="https://www.youtube.com/watch?v=WWLqE1tnf6U&feature=youtu.be" />
  Tarayıcınız video etiketini desteklemiyor.
  </video>
  </div>

---

# **Genel Bilgi**

Kavga etmeye hazır olun! **[Nifty Smashers](https://nifty-league.com/games)** yerel çok oyunculu versiyonu, lansman sırasında hemen kullanıma sunuldu ve ardından çevrimiçi çok oyunculu oldu.

Topluluk arasında savaşın ve arkadaşlarınıza mümkün olduğunca çok yarasa şakası yapın! Nifty Smashers, amacın rakiplerinizi haritadan atarak puan kazanmak olduğu klasik Super Smash Bros oyunundan ilham alıyor.

Klavyenizi veya herhangi bir uyumlu denetleyiciyi (Playstation, Xbox, vb.) kullanarak oynayabilirsiniz. Oyun lobisine girin ve savaş için DEGEN'inizi seçin.

## puanlama

- Bir DEGEN'e bir kez vurulur ve ölürse (haritadan düşerse) 1 puan alırsınız.
- Bir DEGEN, kurtarılamadan birden çok kez vurulursa, DEGEN'in vurulduğu sıklıkta puan alırsınız (önceki isabetlerin başka bir DEGEN tarafından yapılıp yapılmadığına bakılmaksızın - bu nedenle, onları haritadan çıkarmak için son mega-bonk'u indirin ve hak talebinde bulunun tur için tüm puanlar).
- Rakibiniz art arda ne kadar çok zıplarsa, o kadar hızlı zıplarlar ve bonking için o kadar çok puan alırsınız.
- DEGEN'i öldüren son vuruş tüm kombo puanlarını alır.
- Şu anda bir DEGEN'in ne sıklıkla vurulabileceğine (birleşik) ilişkin bir sınır yoktur, ancak alabileceğiniz puan sayısına ilişkin bir sınır vardır (maksimum 3 puan: 2 oyunculu maç / maksimum 5 puan: 3&4 oyunculu maç ).
- 2 oyunculu bir maç, bir tur kazanmak için 5 puan gerektirir.
- 3 & 4 oyunculu maçlar bir tur kazanmak için 10 puan gerektirir.
- Maçlar en iyi 5 turdur.
- 5. raunttan sonra bir beraberlik varsa, berabere kalan oyuncular, diğer oyuncuların kenar çizgiden izleyeceği ani bir ölüm turuna geçerler.

## gecikme

- Gecikme göstergesi, bağlantınızın gecikmesini (ping hızı) gösterir.
- Gecikme tipik olarak ping hızınızın 100ms'nin üzerinde olduğunu gösterir.
- Genel olarak konuşursak, internette oyuncular arasında fiziksel mesafe olduğunda gecikme her zaman mevcuttur. Mesafe ne kadar büyük olursa, gecikme o kadar büyük olur.
- Geliştiricilerin gecikmeyi telafi etmek ve gizlemek için kullandıkları farklı teknikler vardır.
- Mümkün olan en iyi deneyim için gecikmeyi gizleyen bu gecikme telafisi tekniklerinden birkaçını uyguladık.
- Ayrıca, gecikmeyi mümkün olduğunca en aza indirmek için birbirine en yakın oyuncuları eşleştirebilmemiz için dünyanın her yerindeki sunucularla çözümler ekledik. Bu teknikler hakkında daha fazla bilgi edinmekle ilgileniyorsanız, [bu](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html) Gabriel Gambetta'nın Gecikme Telafisi'ni seviyoruz.

## Özel Lobi

- Seçilen bir bölgede bir maç açmak için özel bir lobi kullanılabilir. Lobinin yaratıcısı, lobi haritasında başkalarıyla paylaşılabilecek bir kod görebilir.
- Başka bir degen lobiye katılmak isterse, önce doğru bölgeyi seçmesi ve ardından giriş kutusuna lobi kodunu yazması gerekir.
- Özel bir lobi kodu kullanırken, bölge otomatik olarak değiştirilmelidir.

## Bölgeleri Değiştirme

- Smasher, gecikme/ping'in çok önemli olduğu hızlı tempolu bir oyundur. Seçilen bölge oyuncunun konumuna ne kadar yakınsa, ping o kadar düşük olur.
- Web-GL veya Masaüstü Uygulamasında bölgeyi değiştirdikten sonra mevcut ping görüntülenir.

# **Savaş Temelleri**

## Genel tavsiye

- Şiddetle tavsiye edilen bir oyun kumandası (Playstation, Xbox veya PC/Mac'iniz tarafından tanınan diğer herhangi bir kumanda) ile oynamak.

## Yarasa salıncakları

- Yarasa mümkün olan her yöne sallanabilir: sola, sağa, yukarı, aşağı, köşegenler.
- Yarasa, saldırı düğmesine tıklayarak sallanabilir.
- Düğmeye daha uzun basışlar, sopanın daha sert vurmasını sağlar.
- Yarasa ayakta dururken, koşarken veya zıplarken sallanabilir.
- Oyuncular atlamalar sırasında saldırı düğmesine uzun süre basabilirler - bu genellikle rakiplerinizi şaşırtmak için iyi bir yoldur.

## Hareketli

- 2D Oyun olarak, hareket yönleri sol/sağdır.
- Atlamalar/taklanma sırasında yönler değiştirilebilir (bunu bir kontrolör kullanarak gerçekleştirmek çok daha kolaydır).

## Atlama

- Atlama yüksekliği, atlama düğmesine basma süresi ile değiştirilebilir.
- Atlamalar/takılma sırasında yönler değiştirilebilir.

## uçan hamburger

- Uçan hamburgeri yakalamak DEGEN'inizin sopasını çok daha güçlü hale getirecektir - bu genellikle doğrudan bir öldürme ile sonuçlanır.
- Burger buff süresini zamana ve/veya öldürmeye göre sınırlamayı düşünüyoruz.

# **Kabile Özellikleri**

_Tüm DEGEN kabilelerinin, tüm Nifty League oyunlarında (canlı ve gelecekteki) tutarlı olacak bir Özel Yeteneği ("SA") vardır._

## Özel Yetenekler Listesi

- **Maymun** - Bumerang muzları atın
- **Uzaylı** - Işınlanma
- **Cat** - Atla ve geçici olarak yarasa gücü ve hız artışı elde et
- **Kurbağa** - Dil kıskaçlı kanca
- **Doge** - Doge madeni para rulosu
- **İnsan** - Komut verildiğinde patlayan dinamitleri fırlat

## Yabancı

- SA düğmesine basmak, Alien'in hedeflenen yönde (sol, sağ, yukarı, aşağı, köşegenler) kısa bir mesafe ışınlanmasını sağlar.
- Işınlanan konumda bir enerji patlaması olur ve yakındaki rakipleri vurur.

## Maymun

- SA düğmesine basmak, bir muz bir rakibe çarpana, bir harita parçasına çarpana veya haritadan uçup gidene kadar hedeflenen yöne (sol, sağ, yukarı, aşağı, köşegenler) fırlatır.
- SA düğmesine tekrar basmak, muzun DEGEN'e geri uçmasını sağlayarak bir rakibe tekrar vurmayı mümkün kılar.
- Muzlar bir sopayla vurulabilir ve hedeflenen yöne uçabilir.

## Kedi

- SA'ya basmak kedinin zıplamasını sağlar. Kısa bir süre zıpladıktan sonra kedi güçlenir.
- Güçlendirilmiş yarasa vuruşu, yarasanın daha sert vurduğu anlamına gelir.
- Güçlendirilmiş hareket, kedinin daha hızlı koştuğu anlamına gelir.
- Kediler havada çift zıplayabilir ve zıplayabilir.

## doge

- SA düğmesini basılı tutmak, doge rulosunu yapar.
- Bir rakibe doge roll ile vurmak, onların yuvarlanma yönünde yukarı doğru uçmasını sağlar.
- Doge amaçlanan yönde uçacak.
- Doge roll sırasında, doge roll bitene kadar yönler üç kez değiştirilebilir.
- Doge roll da belli bir süre sonra sona eriyor.

## Kurbağa

- SA düğmesine basmak, Kurbağa'nın dilini vurmasını sağlar.
- Dil bir rakibe çarptığında, o rakip kurbağa yönüne çekilir ve biraz daha uzağa uçar.
- Dil bir harita parçasına çarptığında, kurbağalar kendini o nesneye çeker (örn. duvarlar, tavanlar vb.)
- Dil hedeflenen yönde (sol, sağ, yukarı, aşağı, köşegenler) vurulabilir.

### İnsan

- SA düğmesine basmak, hedeflenen yöne (sol, sağ, yukarı, aşağı, köşegenler) bir bomba atar.
- Bombanın uçuş eğrisi vardır ve muz gibi dümdüz uçmaz (patlatılmazsa yerde kalır).
- Bir süre sonra veya SA düğmesine ikinci kez basıldıktan sonra bomba patlıyor.
- Şu anda bomba, vurarak veya patlama yoluyla bir rakibe çarpabilir.
- Bombalar, patlamasıyla fırlatan DEGEN'in kendisini vurabilen tek SA'dır.
- Bombalar bir sopayla vurulabilir ve hedeflenen yönde uçabilir.
- Oyunu güncellemeyi planlıyoruz, böylece bomba bir rakiple temas ettikten hemen sonra patlayacak. Hiçbir rakibe vurulmazsa, otomatik olarak patlayana kadar veya SA düğmesine ikinci kez bastıktan sonra yerde kalır.

Oyunu nasıl geliştirebileceğimize ve bir sonraki seviyeye taşıyabileceğimize dair geri bildirim ve fikir sağlamak için lütfen **[Discord](https://discord.gg/niftyleague)**
