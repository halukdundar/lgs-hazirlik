# Ek test soruları

Uygulama yerel 10 test bittikten sonra bu klasördeki dosyaları çeker.

- **55 konu** için `{topicId}.json` dosyası
- Her konuda **2 ek test** (toplam ~20 soru)
- Sorular yerel testlerde **kullanılmayan** benzersiz içerikten üretilir

## Yeni soru ekleme

1. `{topicId}.json` dosyasını düzenle
2. `updatedAt` alanını güncelle
3. Commit + push
4. Uygulamada **DAHA FAZLA TEST** → yenile

## Yeniden üretme (geliştirici)

```bash
flutter test test/generate_github_extra_tests_test.dart --plain-name "generate all"
```
