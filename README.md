# Kelime Oyunu - README

Bu Python projesi, kullanıcıya karıştırılmış bir kelime vererek doğru haliyle tahmin yapmasını isteyen basit bir kelime oyunu uygulamasıdır.

## Proje Özeti

Oyunda, kullanıcıya bir kelime karıştırılarak sunulur ve kullanıcının doğru kelimeyi tahmin etmesi beklenir. Eğer tahmin doğruysa, kullanıcı tebrik edilir; yanlışsa, doğru cevap ekrana yazdırılır.

## Kullanım

1. Program çalıştırıldığında, `kelime_listesi` adlı listeden rastgele bir kelime seçilir.
2. Seçilen kelime, harfleri karıştırılarak kullanıcıya gösterilir.
3. Kullanıcıdan bu karışık kelimenin doğru halini tahmin etmesi istenir.
4. Eğer tahmin doğruysa, "Tebrikler! Doğru bildiniz." mesajı görüntülenir.
5. Eğer tahmin yanlışsa, doğru cevap ekrana yazdırılır.

## Kullanıcı Girdisi

- Kullanıcıdan, ekranda gösterilen karışık kelimenin doğru halini tahmin etmesi beklenir.
- Kullanıcı sadece bir kelime girer (örneğin: 'elma', 'armut').

## Fonksiyonlar

### `karistir_kelime(kelime)`
Bu fonksiyon, verilen kelimeyi harflerini karıştırarak yeni bir karışık kelime döndürür.

- **Parametreler**:
  - `kelime` (str): Karıştırılacak kelime.
  
- **Dönüş Değeri**:
  - Karıştırılmış kelime (str).

### `kelime_oyunu()`
Ana fonksiyondur ve oyunun tüm akışını yönetir. Karışık kelimeyi gösterir ve kullanıcının cevabını alır. Sonrasında doğru veya yanlış cevabı kullanıcıya bildirir.

## Kurulum ve Çalıştırma

1. Python yüklü olduğundan emin olun.
2. Proje dosyasını bilgisayarınıza indirin veya kopyalayın.
3. Terminal veya komut satırını açın.
4. Dosyanın bulunduğu klasöre gidin.
5. Aşağıdaki komutu çalıştırarak oyunu başlatın:

```bash
python kelime_oyunu.py
```

## Örnek Çıktı

```
Karışık kelime:  melak
Bu kelimenin doğru hali nedir? elma
Tebrikler! Doğru bildiniz.
```

Ya da yanlış cevap örneği:

```
Karışık kelime:  almut
Bu kelimenin doğru hali nedir? elma
Maalesef, doğru cevap:  armut
```

## Geliştirme ve Katkı

Bu projeye katkıda bulunmak isterseniz, önerilerinizi veya hata düzeltmelerinizi pull request olarak gönderebilirsiniz.
