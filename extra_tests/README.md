# Ek test soruları (GitHub)

Uygulama yerel testler bittikten sonra bu klasördeki JSON dosyalarını çeker.

**Depo:** https://github.com/halukdundar/lgs-hazirlik

## Klasör yapısı

```
extra_tests/
  manifest.json      (isteğe bağlı — hangi konularda ek test var)
  mat_3.json         (konu kimliği = dosya adı)
  fen_1.json
  ...
```

## Yeni soru ekleme

1. İlgili `{topicId}.json` dosyasını aç veya oluştur (`topicId` uygulamadaki konu id'si ile aynı olmalı).
2. `tests` dizisine yeni test ekle veya mevcut teste `questions` ekle.
3. **`updatedAt` alanını güncelle** (ör. `"2026-07-05"`) — uygulama yeni içeriği böyle algılar.
4. Commit + push yap.
5. Uygulamada **DAHA FAZLA TEST** kartına tekrar dokun → GitHub'dan güncel sorular iner.

## JSON örneği

`extra_tests/mat_3.json` dosyasına bakın.
