

## English

A modern FiveM loading screen with a video background, a music player and a built-in mini game.
Everything is customised from a single settings file (`config.js`); no coding required.

### Features

**Background**
- YouTube video or an image slideshow
- Falls back to images automatically if YouTube fails, so the screen never stays black
- Play the video's own sound or your own playlist

**Music player**
- Playlist, previous / next, volume control
- Players pick the sound source themselves with a "Music | Video" switch
- Volume and source choice are remembered for the next visit

**Welcome and loading**
- A centred "Welcome" title with the player's name and animated rotating messages
- A clean loading bar showing the real loading percentage
- Status text that changes with each loading stage

**Info panel**
- Slides in from the left edge with a single button
- Staff, Rules, Keybinds and Gallery tabs
- Discord, website and store buttons in the top right

**Mini game**
- A slither-style snake game to play while waiting
- Rival snakes, live ranking, score and best-score tracking
- A hard-to-catch "super food": the snake that eats it grows 8-9 times longer at once
- Video and music pause while the game is open and resume when it closes

### Installation

1. Place the folder in your server's `resources` folder.
2. Add this line to `server.cfg`: `ensure NtLoading.V3`
3. Open `html/config.js` and enter your own details.
4. Restart the server.

### Configuration

Everything lives in `html/config.js`, with a comment next to each setting:
server name and logo, colours, font, button and tab labels, background video, playlist,
staff list, rules, keybinds, social buttons, loading texts and mini game options.

The default texts are in Turkish; translate them in the same file.

### Notes

- No external libraries.
- Local videos must be in `.webm` format; FiveM does not play `.mp4`.
- You are responsible for the rights to any video and music you use.

---

## Türkçe

Video arka planlı, müzik çalarlı ve mini oyunlu modern bir FiveM yükleme ekranı.
Tek bir ayar dosyasından (`config.js`) tamamen kişiselleştirilir; kod bilgisi gerekmez.

### Özellikler

**Arka plan**
- YouTube videosu ya da resim slaytı
- YouTube açılmazsa otomatik olarak resimlere geçer, ekran siyah kalmaz
- İsterseniz videonun kendi sesi, isterseniz kendi şarkı listeniz çalar

**Müzik çalar**
- Şarkı listesi, önceki / sonraki, ses ayarı
- Oyuncu "Müzik | Video" anahtarıyla ses kaynağını kendisi seçer
- Ses seviyesi ve seçim bir sonraki girişte hatırlanır

**Karşılama ve yükleme**
- Ortada oyuncunun adıyla "Hoş geldin" yazısı ve animasyonla değişen mesajlar
- Gerçek yükleme yüzdesini gösteren sade yükleme çubuğu
- Aşamaya göre değişen durum yazıları

**Bilgi paneli**
- Sol kenardaki butonla yandan açılır
- Ekip, Kurallar, Tuşlar ve Galeri sekmeleri
- Sağ üstte Discord, web sitesi ve mağaza butonları

**Mini oyun**
- Beklerken oynanan slither tarzı yılan oyunu
- Rakip yılanlar, canlı sıralama, skor ve en iyi skor kaydı
- Yakalaması zor "süper yem": yiyen yılan bir anda 8-9 katına çıkar
- Oyun açıkken video ve müzik durur, kapatınca devam eder

### Kurulum

1. Klasörü sunucunuzun `resources` klasörüne koyun.
2. `server.cfg` dosyasına ekleyin: `ensure NtLoading.V3`
3. `html/config.js` dosyasını açıp kendi bilgilerinizi yazın.
4. Sunucuyu yeniden başlatın.

### Ayarlar

Her şey `html/config.js` dosyasındadır ve her ayarın yanında açıklaması yazar:
sunucu adı ve logo, renkler, yazı tipi, buton ve sekme yazıları, arka plan videosu,
şarkı listesi, ekip listesi, kurallar, tuşlar, sosyal medya butonları, yükleme yazıları
ve mini oyun ayarları.

### Notlar

- Harici kütüphane kullanmaz.
- Yerel video kullanacaksanız `.webm` biçiminde olmalıdır; FiveM `.mp4` oynatmaz.
- Kullandığınız video ve müziklerin kullanım hakkı size aittir.
