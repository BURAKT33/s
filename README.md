# s

Polybius karesi ve DES-ECB ile kısa bir şifreleme denemesi. Metin önce Polybius koordinatlarına çevrilir, sonra DES ile şifrelenir. Çözme ters sırada yapılır.

Bu bir ders örneğidir. Anahtar `python12.py` içinde sabittir ve DES-ECB gerçek veri için uygun değildir.

## Kurulum

```bash
pip install pycryptodome
```

## Çalıştırma

```bash
python python12.py
```

İstendiğinde bir mesaj yazın. Betik şifreli metni (hex) ve çözülmüş metni basar. Polybius tablosu J harfini içermez; harf olmayan karakterler atılır.
