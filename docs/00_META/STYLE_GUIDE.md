| Alan | Değer |
|---|---|
| ID | MET-005 |
| Başlık | Yazım Standardı ve Doküman Yaşam Döngüsü |
| Versiyon | 1.0 |
| Durum | Onaylandı |
| Sahip | yyuzuak |
| Bağımlılıklar | MET-001 |
| Son Güncelleme | 2026-07-12 |

# Yazım Standardı ve Doküman Yaşam Döngüsü

## Amaç / Kapsam

Bu belge iki şeyi tanımlar: (1) bir belgenin taslaktan onaylı hale gelene kadar geçtiği durumlar, (2) belge içeriğinin nasıl yazılması gerektiği.

## Doküman Yaşam Döngüsü

```
Taslak → İnceleme → Onaylandı → Kullanımdan Kaldırıldı
```

| Durum | Anlamı | Referans Verilebilir mi? |
|---|---|---|
| Taslak | Yazım aşamasında, içerik değişebilir. | Hayır |
| İnceleme | İçerik tamamlandı, kullanıcı onayı bekliyor. | Hayır |
| Onaylandı | Resmi kaynak. | Evet |
| Kullanımdan Kaldırıldı | Artık geçerli değil; geçmiş referans bütünlüğü için silinmez, yerine geçen belge ID'si metadata'da belirtilir. | Hayır (yeni içerik için) |

Durum geçiş kuralı: Taslak → İnceleme geçişini belgeyi yazan yapar. İnceleme → Onaylandı geçişini **yalnızca kullanıcı** yapar. Hiçbir belge kullanıcı onayı olmadan "Onaylandı" durumuna geçemez.

## Yazım Standardı

Her belge [MET-001](DOCUMENT_STANDARD.md)'de tanımlanan iskelete uyar:

1. Metadata tablosu
2. Başlık (H1)
3. Amaç / Kapsam
4. Ana İçerik (H2 bölümler)
5. Açık Sorular / Kararsız Noktalar
6. Değişiklik Geçmişi

### Dil ve Ton

- Türkçe, teknik, net.
- Öznel/yaratıcı yorum yok — bu bir tasarım dokümanı değil, spesifikasyondur.
- Her iddia gerekçelendirilir veya kaynağına link verilir.
- Belirsiz noktalar "Açık Sorular" bölümüne yazılır, ana metne karıştırılmaz.

## Değişiklik Geçmişi

| Versiyon | Tarih | Özet |
|---|---|---|
| 1.0 | 2026-07-12 | İlk yayın. |
