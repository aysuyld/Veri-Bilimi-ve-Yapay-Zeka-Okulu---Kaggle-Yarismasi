# Veri Bilimi ve Yapay Zeka Okulu Kaggle Yarismasi
Bu yarışmada amaç, value_increased sütununu True/False olarak doldurarak, oyuncuların piyasa değerinin artış gösterip göstermediğini tahmin etmektir.

### İçerik
- id: Her oyuncu için benzersiz bir sayısal kimlik.
- value_increased: Oyuncunun piyasa değerinin artıp artmadığını gösteren değer. "True" veya "False". 👉 Tahmin edilecek sütun
- Ability: Oyuncunun mevcut genel yetenek puanı, genellikle 0 ile 100 arasında.
- Potential: Oyuncunun gelecekte ulaşabileceği maksimum potansiyel yetenek puanı, genellikle 0 ile 100 arasında.
- Positions: Oyuncunun oynayabileceği pozisyonlar örneğin, GK Kaleci, ST Forvet.
- Caps / Goals: Oyuncunun milli takımda oynadığı maç sayısı caps ve attığı gol sayısı.
- Foot: Oyuncunun tercih ettiği ayak örneğin, Sağ, Sol.
- Height: Oyuncunun boyu, genellikle santimetre cinsinden.
- Weight: Oyuncunun kilosu, genellikle kilogram cinsinden.
- Aerial Reach: Kalecinin yüksek toplara ulaşma yeteneği.
- Command of Area: Kalecinin ceza sahasını kontrol etme yeteneği.
- Communication: Kalecinin savunma oyuncularıyla etkili iletişim kurma yeteneği.
- Eccentricity: Kalecinin beklenmedik veya sıradışı hareketler yapma eğilimi.
- Handling: Kalecinin topu yakalama ve tutma yeteneği.
- Kicking: Kalecinin topu uzun mesafeye doğru ve isabetli şut çekme yeteneği.
- One on Ones: Kalecinin bire bir pozisyonlarda başarılı olma yeteneği.
- Reflexes: Kalecinin hızlı tepkiler vererek kurtarış yapma yeteneği.
- Rushing Out Tendency: Kalecinin kale çizgisinden çıkıp topa müdahale etme eğilimi.
- Tendency to Punch: Kalecinin topu yakalamak yerine yumruklamayı tercih etme eğilimi.
- Throwing: Kalecinin topu uzun mesafeye ve isabetli bir şekilde atma yeteneği.
- Corners: Oyuncunun korner vuruşlarındaki yeteneği.
- Crossing: Oyuncunun kenar bölgelerden isabetli orta yapma yeteneği.
- Dribbling: Oyuncunun top sürme ve kontrol yeteneği.
- Finishing: Oyuncunun gol fırsatlarını bitirme yeteneği.
- First Touch: Oyuncunun topa ilk dokunuşta kontrol etme yeteneği.
- Free Kick Taking: Oyuncunun serbest vuruşlardaki yeteneği.
- Heading: Oyuncunun kafa vuruşundaki becerisi, hem hücumda hem de savunmada.
- Long Shots: Oyuncunun uzak mesafeden isabetli şut çekme yeteneği.
- Long Throws: Oyuncunun uzun mesafeye taç atma yeteneği.
- Marking: Savunma oyuncusunun rakip oyuncuyu markaj altına alma yeteneği.
- Passing: Oyuncunun pas isabeti ve pas mesafesi konusundaki yeteneği.
- Penalty Taking: Oyuncunun penaltı vuruşlarındaki yeteneği.
- Tackling: Savunma oyuncusunun rakipten top kapma yeteneği.
- Technique: Oyuncunun dripling, pas gibi teknik becerilerdeki yeteneği.
- Aggression: Oyuncunun fiziksel olarak agresif olma eğilimi.
- Anticipation: Oyuncunun topun nereye gideceğini tahmin edip doğru zamanda müdahale etme yeteneği.
- Bravery: Oyuncunun riskli veya tehlikeli pozisyonlarda oynamaya cesaret etmesi.
- Composure: Oyuncunun baskı altında sakin kalma yeteneği, özellikle gol pozisyonlarında.
- Concentration: Oyuncunun maç boyunca dikkatini kaybetmeden odaklanabilme yeteneği.
- Decisions: Oyuncunun doğru kararları hızlı ve doğru şekilde alabilme yeteneği.
- Determination: Oyuncunun kazanma arzusu ve azmi.
- Flair: Oyuncunun hücumda yaratıcı ve beklenmedik hareketler yapma yeteneği.
- Leadership: Oyuncunun takım arkadaşlarını motive etme ve yönlendirme yeteneği.
- Off the Ball: Oyuncunun topsuz alanda doğru pozisyon alma ve hareket etme yeteneği.
- Positioning: Savunma oyuncusunun doğru pozisyon alma becerisi.
- Teamwork: Oyuncunun takım arkadaşlarıyla uyum içinde oynama yeteneği.
- Vision: Oyuncunun sahada geniş açıyla oyunu okuyup etkili paslar yapabilme yeteneği.
- Work Rate: Oyuncunun maç boyunca yoğun çaba gösterme yeteneği.
- Acceleration: Oyuncunun hızını kısa sürede en üst seviyeye çıkarma yeteneği.
- Agility: Oyuncunun denge ve çeviklik konusundaki becerisi.
- Balance: Oyuncunun topa sahipken ya da baskı altında dengesini koruma yeteneği.
- Jumping Reach: Oyuncunun zıplama yüksekliği, genellikle savunma oyuncuları ve kaleciler için önemlidir.
- Natural Fitness: Oyuncunun genel kondisyon ve dayanıklılık seviyesi.
- Pace: Oyuncunun uzun mesafede hız yapma yeteneği.
- Stamina: Oyuncunun maç boyunca yüksek performans sergileyebilme yeteneği.
- Strength: Oyuncunun fiziksel gücü ve rakiplerine karşı koyma yeteneği.

Not:  22/23 Sezon Başı piyasa değeri $5M altında, 24/25 Sezon Başı piyasa değeri ise $10M ve üzerinde olan oyuncular piyasa değeri artmış, yani value_increased kabul edilir.

Link: https://www.kaggle.com/competitions/veri-bilimi-ve-yapay-zeka-okulu-kaggle-yarismasi/overview

### Skorlar
Private Score   ->  0.25
Public Score    ->  0.29

### Sonuçlar ve Değerlendirme
Bu projede, veri seti üzerinde çeşitli analizler ve modelleme çalışmaları gerçekleştirdim. Analiz sonucunda elde edilen model doğruluk oranı 1.0 olsa da, yarışmadaki F1 skoru metriği esas alındığında puanım 0.25 olarak hesaplandı. Bu durumun nedeni, modelin veri setine uygun tahminler üretememesi veya overfitting yapması olabilir.
Bu proje, kendi bilgi ve becerilerimi geliştirirken yaptığım hatalardan ders çıkarmam için önemli bir fırsat sundu. Hataların ve eksikliklerin farkında olmak, öğrenme sürecimin bir parçası. Bu yüzden, projemde gördüğünüz hataları veya eksiklikleri bana bildirerek, beni daha doğru bir yola yönlendirme fırsatı verirseniz çok mutlu olurum. Geri bildirimleriniz sayesinde kendimi geliştirebilir ve gelecekte daha iyi projeler ortaya koyabilirim.
