# NoProfanity - Turkish Anti-Swear Bot

NoProfanity, Türkçe dilinde küfür ve argo tespitine odaklanan açık kaynaklı bir Python modülüdür.  
Metinlerde geçen rahatsız edici kelimeleri filtrelemek veya tespit etmek isteyen geliştiriciler için uygundur.

---

NoProfanity is an open-source Python module focused on detecting profanity and slang in the Turkish language.  
It is suitable for developers who want to filter or detect offensive words in texts.

---

## Özellikler | Features

- Türkçe küfür/argo kelime tespiti  
- Python ile kolay entegrasyon  
- Temizleme (sanitize) veya tespit (detect) seçenekleri  
- Discord botları, forumlar veya chatbot sistemlerinde kullanılabilir

---

- Turkish profanity/slang detection  
- Easy integration with Python  
- Supports cleaning or detecting  
- Suitable for Discord bots, forums, or chatbot systems

---

## Gereksinimler | Requirements

- Python 3.x

---

## Kurulum | Installation

```bash
git clone https://github.com/nat-heo/noprofanity_turkish_antiswear_bot.git
cd noprofanity_turkish_antiswear_bot
```

> Gerekirse modülünüzü `pip install -e .` komutu ile geliştirici modunda yükleyebilirsiniz.  
> You can also install it in editable mode with `pip install -e .` if needed.

---

## Kullanım | Usage

### Basit Örnek | Simple Example

```python
from noprofanity import check_profanity

text = "bu ne biçim saçma sapan küfürlü bir cümle"
if check_profanity(text):
    print("Uygunsuz içerik tespit edildi.")
else:
    print("Temiz içerik.")
```

---

## Katkıda Bulunma | Contributing

1. Fork yap  
2. Yeni bir dal oluştur: `git checkout -b feature/yenilik`  
3. Geliştirme yap, commit et  
4. Push ve PR gönder

---

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/new-feature`  
3. Make your changes and commit  
4. Push and submit a pull request

---

## Yasal Uyarı | Legal Disclaimer

Bu yazılım yalnızca eğitim, deneysel ve içerik filtreleme amaçlıdır.  
Hiçbir kişi veya gruba karşı hedef alınarak kullanılmamalıdır.  

Kütüphane tarafından kullanılan kelime listeleri, çeşitli kaynaklardan derlenmiştir ve zamanla değişebilir.  
Geliştirici, üçüncü parti kullanım sonucu oluşabilecek herhangi bir durumdan sorumlu değildir.

---

This software is intended solely for educational, experimental, and content filtering purposes.  
It must not be used to target or discriminate against any individual or group.  

The word lists used by the library are compiled from various sources and may change over time.  
The developer is not responsible for any consequences arising from third-party usage.

---

## İletişim | Contact

Geri bildirim veya öneri için [issues](https://github.com/nat-heo/noprofanity_turkish_antiswear_bot/issues) bölümünü kullanabilirsiniz.  
You can use the [issues](https://github.com/nat-heo/noprofanity_turkish_antiswear_bot/issues) section for feedback or suggestions.

---
