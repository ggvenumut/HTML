## HTML’in Temelleri

1. **HTML Nedir?**

HTML (HyperText Markup Language), bir web sayfasının yapısını oluşturmak için kullanılan bir işaretleme dilidir. HTML, içeriğin düzenlenmesini ve tarayıcının bunu anlamasını sağlar.

2. **HTML’in Temel Yapısı** 

Bir HTML belgesi, aşağıdaki gibi bir temel yapıya sahiptir:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Başlık</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, HTML ile oluşturulmuş bir paragraftır.</p>
</body>
</html>


```

Bu Yapının Mantığı:

1. `<!DOCTYPE html>`: HTML5 kullanıldığını belirtir.
2. `<html>`: Tüm HTML içeriğini kapsar.
3. `<head>`: Sayfa ile ilgili meta bilgiler (başlık, karakter seti vb.) buraya eklenir.
4. `<body>`: Kullanıcının tarayıcıda gördüğü tüm içerik buraya yazılır.

3.**En Temel HTML Etiketleri**

- Başlık Etiketleri (`<h1> - <h6>`):
    - Sayfa başlıklarını belirtmek için kullanılır.
    - `<h1>` en büyük, `<h6>` en küçük başlıktır.
```html
<h1>En Büyük Başlık</h1>
<h2>İkinci Büyük Başlık</h2>
<h3>Üçüncü Büyük Başlık</h3>
<h4>Dördüncü Büyük Başlık</h4>
<h5>Beşinci Büyük Başlık</h5>
<h6>Altıncı Büyük Başlık</h6>
```

- Paragraflar (`<p>`):

Metin eklemek için kullanılır.

```html
<p>Bu bir paragraftır.</p>
```

- Linkler (`<a>`):

Bir bağlantı oluşturur.


```html
<a href="https://www.google.com">Google'a Git</a>
```

- Görseller (`<img>`):

Bir görsel eklemek için kullanılır.

```html
<img src="gorsel.jpg" alt="Görsel Açıklaması">
```

- Listeler:
     - Sırasız Liste (`<ul>`):
    ```html
    <ul>
        <li>Madde 1</li>
        <li>Madde 2</li>
    </ul>
    ```

    - Sıralı Liste (`<ol>`):
    ```html
    <ol>
        <li>Birinci Madde</li>
        <li>İkinci Madde</li>
    </ol>

    ```