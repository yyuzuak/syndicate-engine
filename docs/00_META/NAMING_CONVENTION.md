| Alan | Değer |
|---|---|
| ID | MET-002 |
| Başlık | Belge Numaralandırma ve Adlandırma Kuralı |
| Versiyon | 1.0 |
| Durum | Onaylandı |
| Sahip | yyuzuak |
| Bağımlılıklar | MET-001 |
| Son Güncelleme | 2026-07-12 |

# Belge Numaralandırma ve Adlandırma Kuralı

## Amaç / Kapsam

Bu belge, her markdown dosyasına atanacak benzersiz ID'nin nasıl üretileceğini ve dosya adlandırma kuralını tanımlar. Amaç, bir belge taşınsa veya başlığı değişse bile çapraz referansların kırılmamasıdır.

## Domain Klasör Kodları

| Klasör | Kod |
|---|---|
| 00_META | MET |
| 01_FOUNDATION | FOU |
| 02_SIMULATION | SIM |
| 03_WORLD | WOR |
| 04_ENTITIES | ENT |
| 05_CHARACTER | CHA |
| 06_ORGANIZATION | ORG |
| 07_ECONOMY | ECO |
| 08_BUSINESS | BUS |
| 09_OPERATIONS | OPE |
| 10_POLITICS | POL |
| 11_LAW | LAW |
| 12_AI | AIX |
| 13_TECH | TEC |
| 14_DATABASE | DAT |
| 15_UI_UX | UIX |
| 16_BALANCE | BAL |
| 17_LIVEOPS | LIV |
| 18_LORE | LOR |

## Belge ID Şeması

Format: `[DOMAIN_KODU]-[3 haneli sıra no]`, örn. `ECO-004`.

Sıra numarası, o domain klasörü içinde 001'den başlayarak artan sırayla verilir. Bir belge kullanımdan kaldırılsa bile numarası tekrar kullanılmaz.

## Dosya Adlandırma

Dosya adı: `[ID]-kisa-slug.md`

Örnek: `ECO-004-temel-para-birimi.md`

Slug kuralları: küçük harf, Türkçe karakter yok (a/c/g/i/o/s/u ile transliterasyon), kelimeler tire (`-`) ile ayrılır.

## Klasör Numaralandırma Boşluk Stratejisi

Mevcut domain klasörleri (`00`–`18`) sabittir ve yeniden numaralandırılmaz. Yeni bir domain gerekirse:

- Mevcut iki domain arasına eklenecekse: harf eki kullanılır (örn. `07A_TRADE`).
- Sona eklenecekse: bir sonraki tam sayı kullanılır (örn. `19_AUDIO`).

## Değişiklik Geçmişi

| Versiyon | Tarih | Özet |
|---|---|---|
| 1.0 | 2026-07-12 | İlk yayın. |
