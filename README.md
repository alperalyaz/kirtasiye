# Bahçeşehir Koleji Denizli – 3. Sınıf Kırtasiye Listesi (2025–2026)

Özel Denizli Bahçeşehir Koleji'nin 3. sınıflar için yayınladığı kırtasiye listesinin,
alışverişte kullanılabilir hale getirilmiş tek sayfalık hali.

**Liste:** https://alperalyaz.github.io/kirtasiye/

## Neden

Okulun listesi Türkçe, Matematik, Fen, İngilizce, Almanca, Görsel Sanatlar, Beden
E�itimi ve Yüzme diye ayrı ayrı yazılmış. Markette elinde 8 ayrı başlık dolaşmak
zor oluyor; "beşer adet kurşun kalem ve ikişer adet başlık kalemi" gibi satırları
raf önünde çözmek de öyle.

Bu sayfa hepsini tek listeye indiriyor:

- 57 kalem, tek akış halinde, market rafı sırasına yakın
- Her satırda adet, hangi dersin istediği ve kabaca fiyat tahmini
- Aldıkça dokun, tiklensin; evde varsa iki kez dokun, üstü çizilsin
- Üstte "kalan ~X TL" sayacı
- "Sadece kalanlar" düğmesi ile alınanları gizleme
- İşaretler telefonda saklanır, sayfayı kapatıp açınca durur

## Notlar

- Sayfa bir veli tarafından hazırlandı, okulun resmî sayfası değildir.
- Kaynak: okulun 2025–2026 için yayınladığı "3. Sınıf Kırtasiye Listesi" PDF'i.
- Fiyatlar Eylül 2026 için kaba tahmindir; mağazaya ve markaya göre değişir.
- Bahçeşehir Koleji logolu eşofman ve tişört kırtasiyede satılmaz, okuldan alınır.
- Okulun notu: elinizde olan malzemeyi tekrar almanıza gerek yok.

## Hata veya güncelleme

Listede eksik/yanlış gördüyseniz ya da okul listeyi güncellediyse
[issue açın](https://github.com/alperalyaz/kirtasiye/issues).

## Teknik

Tek dosya, `index.html`. Çerçeve yok, derleme yok. GitHub Pages'te barınıyor.
İşaretler varsayılan olarak tarayıcıda (localStorage) tutulur.

Aynı listeyi iki kişinin ortak tiklemesi için adresin sonuna bir oda anahtarı
eklenir: `?oda=birseyler`. O modda işaretler Supabase'de ortak tutulur ve
anahtarı bilen herkes aynı listeyi görür.
