# lgs-hazirlik

LGS Hazırlık uygulaması için **ek test soruları** deposu.

Uygulama yerel testler bittikten sonra `extra_tests/` klasöründeki JSON dosyalarını çeker.

## Klasör yapısı

```
extra_tests/
  manifest.json
  mat_3.json
  ...
```

## Yeni soru ekleme

1. `extra_tests/{topicId}.json` dosyasını oluştur veya güncelle.
2. `updatedAt` alanını güncelle.
3. Commit + push yap.
4. Uygulamada **DAHA FAZLA TEST** kartına dokun.

Detaylı format: [extra_tests/README.md](extra_tests/README.md)
