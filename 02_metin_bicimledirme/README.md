##  Metin Biçimlendirme

HTML'de metin biçimlendirme, bir web sayfasında metinlerin nasıl görüneceğini ve yapılandırılacağını belirler. İşte sırasıyla her madde:

---

1. **Başlık Etiketleri** (`<h1> - <h6>`)

- **Amaç**: Metinleri başlıklar halinde düzenlemek için kullanılır.
- **Hiyerarşi**: `<h1>` en büyük, `<h6>` en küçük başlıktır. Sayfa başlığında genellikle sadece bir `<h1>` etiketi kullanılır.

**Örnek**:
```html
<h1>Bu En Büyük Başlık</h1>
<h2>Bu İkinci Büyük Başlık</h2>
<h3>Bu Üçüncü Büyük Başlık</h3>
<h4>Bu Dördüncü Büyük Başlık</h4>
<h5>Bu Beşinci Büyük Başlık</h5>
<h6>Bu Altıncı Büyük Başlık</h6>
```

**Not**

Başlık etiketleri, arama motoru optimizasyonu (SEO) için de önemlidir. Doğru hiyerarşi kullanılmalıdır.

---


2.  **Paragraflar** (`<p>`)

- **Amaç**: Normal metinler için kullanılır.
- Birden fazla paragraf oluşturulabilir ve her bir paragraf kendi `<p>` etiketi içinde olmalıdır.

```html
<p>Bu birinci paragraftır. HTML ile metin biçimlendirme yapıyoruz.</p>
<p>Bu ikinci paragraftır. Metinleri farklı satırlara bölebiliriz.</p>

```

---

3. **Kalın ve İtalik Metin**

- Kalın Metin:

    - `<b>`: Görsel olarak kalın yapar, anlam ifade etmez.
    - `<strong>`: Kalın yapar ve anlam katar (arama motorları tarafından daha önemli kabul edilir).

```html
<p>Bu <b>kalın</b> bir metindir.</p>
<p>Bu <strong>daha önemli</strong> bir metindir.</p>

```
- İtalik Metin:
    - `<i>`: Görsel olarak italik yapar.
    - `<em>`: İtalik yapar ve anlam katar (vurgu amaçlıdır).

```html
<p>Bu <i>italik</i> bir metindir.</p>
<p>Bu <em>vurgu yapılmış</em> bir metindir.</p>
```
---
4. **Alıntılar ve Ön Biçimlendirilmiş Metin**
- Blok Alıntılar (`<blockquote>`):
    - Uzun alıntılar için kullanılır.
    - Genellikle girintili bir biçimde görüntülenir

```html
<blockquote>
    "Başarı, cesaretle çalışmanın ve azmin sonucudur."
</blockquote>

```

- Ön Biçimlendirilmiş Metin (`<pre>`):

    - Metni olduğu gibi gösterir (boşluklar ve satır sonları korunur).
    - Kod yazarken kullanışlıdır.

```html 
<pre>
    Bu bir ön biçimlendirilmiş metindir.
    Satır başları ve boşluklar korunur.
</pre>
```

5. Listeler (Sıralı ve Sırasız)

- Sırasız Liste (`<ul>`):
    - Liste öğelerini madde işaretleriyle sıralar.

```html
<ul>
    <li>Elma</li>
    <li>Armut</li>
    <li>Muz</li>
</ul>
```

- Sıralı Liste (`<ol>`):
    - Liste öğelerini numaralarla sıralar.

```html 
<ol>
    <li>Birinci</li>
    <li>İkinci</li>
    <li>Üçüncü</li>
</ol>

```