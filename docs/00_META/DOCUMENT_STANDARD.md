| Alan | Değer |
|---|---|
| ID | MET-001 |
| Başlık | Doküman Standardı |
| Versiyon | 1.0 |
| Durum | Onaylandı |
| Sahip | yyuzuak |
| Bağımlılıklar | MET-002, MET-003, MET-004, MET-005 |
| Son Güncelleme | 2026-07-12 |

# Doküman Standardı

## Amaç / Kapsam

Bu belge, Syndicate Engine bilgi tabanındaki her markdown dosyasının uyması gereken zorunlu yapıyı tanımlar. Amaç, tüm belgelerin bir yazılım spesifikasyonu gibi tutarlı, izlenebilir ve makine/insan tarafından aynı şekilde okunabilir olmasını sağlamaktır.

## Zorunlu Metadata Tablosu

Her belgenin en başında, başlıktan önce şu tablo bulunur:

```markdown
| Alan | Değer |
|---|---|
| ID | (benzersiz belge kimliği, bkz. MET-002) |
| Başlık | |
| Versiyon | (MAJOR.MINOR, bkz. MET-004) |
| Durum | Taslak / İnceleme / Onaylandı / Kullanımdan Kaldırıldı (bkz. MET-005) |
| Sahip | |
| Bağımlılıklar | (bu belgenin referans verdiği diğer belge ID'leri) |
| Son Güncelleme | (YYYY-MM-DD) |
```

Alanlardan hiçbiri boş bırakılamaz. Bağımlılık yoksa "Yok" yazılır.

## Belge İskeleti

Metadata tablosundan sonra her belge şu sırayla ilerler:

1. **Başlık (H1)**
2. **Amaç / Kapsam** — belgenin ne için var olduğunu 1 paragrafta anlatır.
3. **Ana İçerik** — H2 bölümler halinde.
4. **Açık Sorular / Kararsız Noktalar** — varsa; yoksa bölüm "Yok" ile bırakılır.
5. **Değişiklik Geçmişi** — tablo: `Versiyon | Tarih | Özet`.

## Yazım Dili

Türkçe, teknik ve net. Öznel yorum yok. Her iddia gerekçelendirilir. Belirsizlik varsa "Açık Sorular" bölümüne taşınır, ana içeriğe karışık yazılmaz.

## Değişiklik Geçmişi

| Versiyon | Tarih | Özet |
|---|---|---|
| 1.0 | 2026-07-12 | İlk yayın. |
