assets/brand/vertical_logo.svg içinde şunları yaptım:

Gömülü 2 PNG — Siyah/beyaz görünümü (siyah logo + beyaz zemin) korunarak tonlar 
#152240 ile yeniden boyandı; kenar yumuşaklığı (gray) luminance ile beyaza doğru karıştırıldı.
Vektör fill="#000000" — fill="#152240" olacak şekilde güncellendi.
index.html zaten hero’da ./assets/brand/vertical_logo.svg kullanıyor; ekstra bir değişiklik gerekmedi.

Not: Dark’da hero’da filter: invert(1) var; renkli logo ters çevirileceği için koyu temada ton farklı görünecek. Daha sonra sadece siyah logo istersen git checkout -- assets/brand/vertical_logo.svg ile bu dosyayı geri alabilirsin (veya bir yedekten kopyalayabilirsin).

-------------
Özet: Beğendiğin şey aslında 
#152240’nın tersi; tasarımda bilerek kullanmak istersen dark mod için bu 
#EADDBF (veya biraz ayarlanmış tonları) hedef renk olarak verebilirsin.

Logo dosyasının bozulmasından şikâyet ediyorsan bir sonraki adım: assets/old-logos/vertical_logo.svg’yi tekrar assets/brand/vertical_logo.svg olarak kopyalayıp (saf siyah logo), dark modda ise ya bu krem tonunu ayrı bir SVG/CSS ile vermek en temiz yol olur; istersen bunu birlikte netleştirebiliriz.