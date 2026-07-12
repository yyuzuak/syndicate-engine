| Alan | Değer |
|---|---|
| ID | MET-003 |
| Başlık | Belge Referans Sistemi |
| Versiyon | 1.0 |
| Durum | Onaylandı |
| Sahip | yyuzuak |
| Bağımlılıklar | MET-001, MET-002 |
| Son Güncelleme | 2026-07-12 |

# Belge Referans Sistemi

## Amaç / Kapsam

Bu belge, belgeler arası atıfların nasıl yapılacağını tanımlar. Amaç, aynı bilginin birden fazla dosyada tekrar edilmesini (kural 4) önlemek ve bağımlılıkların izlenebilir olmasını sağlamaktır.

## Temel Kural: İçerik Kopyalanmaz, Link Verilir

Bir belge başka bir belgede zaten tanımlı bir bilgiye ihtiyaç duyduğunda, o bilgiyi yeniden yazmaz; kaynak belgeye referans verir.

## Metadata Üzerinden Bağımlılık Bildirimi

Bir belge, referans verdiği tüm belgelerin ID'lerini kendi metadata tablosundaki **Bağımlılıklar** alanına yazar:

```
| Bağımlılıklar | ECO-004, ORG-001 |
```

## Metin İçi Atıf Formatı

Gövde metninde bir belgeye atıf yapılırken hem ID hem markdown link birlikte kullanılır:

```markdown
[ECO-004](../07_ECONOMY/ECO-004-temel-para-birimi.md)
```

Göreli yol (`../`) kullanılır; mutlak dosya sistemi yolu kullanılmaz.

## Bağımlılık Döngüsü Yasağı

İki belge birbirine dairesel (A→B→A) bağımlı olamaz. Böyle bir ihtiyaç doğarsa, ortak bilgi üçüncü bir belgeye çıkarılır ve her ikisi ona referans verir.

## Kullanımdan Kaldırılan Belgelere Referans

Bir belge "Kullanımdan Kaldırıldı" durumuna geçtiğinde, ona referans veren tüm belgeler güncellenerek yerine geçen belgenin ID'sine yönlendirilir.

## Değişiklik Geçmişi

| Versiyon | Tarih | Özet |
|---|---|---|
| 1.0 | 2026-07-12 | İlk yayın. |
