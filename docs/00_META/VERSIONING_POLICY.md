| Alan | Değer |
|---|---|
| ID | MET-004 |
| Başlık | Versiyonlama Standardı |
| Versiyon | 1.0 |
| Durum | Onaylandı |
| Sahip | yyuzuak |
| Bağımlılıklar | MET-001, MET-005 |
| Son Güncelleme | 2026-07-12 |

# Versiyonlama Standardı

## Amaç / Kapsam

Bu belge, her dokümanın versiyon numarasının nasıl artırılacağını tanımlar. Amaç, bir belgeye bağımlı diğer belgelerin ne zaman gözden geçirilmesi gerektiğini net şekilde işaretlemektir.

## Format

`MAJOR.MINOR` (örn. `1.0`, `1.1`, `2.0`). Belge ilk "Onaylandı" durumuna geçtiğinde `1.0` ile başlar; "Taslak"/"İnceleme" aşamasında versiyon `0.x` olabilir.

## Artış Kuralları

- **MAJOR artışı**: Belgeye bağımlı diğer belgeleri etkileyecek veya onlarla çelişecek bir değişiklik yapıldığında (örn. bir tanımın anlamının değişmesi, bir kuralın kaldırılması). MAJOR arttığında, bu belgeye bağımlı tüm belgeler (bkz. [MET-003](REFERENCE_SYSTEM.md)) gözden geçirilmelidir.
- **MINOR artışı**: Açıklama ekleme, yazım düzeltmesi, örnek ekleme gibi geriye dönük uyumlu değişikliklerde.

## Belge İçi Değişiklik Geçmişi

Her belgenin sonunda bulunan "Değişiklik Geçmişi" tablosuna her versiyon artışında bir satır eklenir: `Versiyon | Tarih | Özet`.

## Merkezi Değişiklik Günlüğü

`docs/00_META/CHANGELOG.md`, tüm belgelerdeki **MAJOR** versiyon değişikliklerinin merkezi, tek satırlık özetini tutar (detay içermez, sadece hangi belgenin ne zaman kırıcı değişiklik geçirdiğini gösterir).

## Değişiklik Geçmişi

| Versiyon | Tarih | Özet |
|---|---|---|
| 1.0 | 2026-07-12 | İlk yayın. |
