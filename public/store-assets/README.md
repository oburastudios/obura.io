# Play Store görselleri

Google Play Console → Main store listing için hazırlanan görseller.

| Dosya | Boyut | Kullanım |
| --- | --- | --- |
| `icon-512.png` | 512×512 | Uygulama ikonu (App icon) |
| `feature-graphic.png` | 1024×500 | Öne çıkan görsel (Feature graphic) |
| `shot-01…08-*.png` | 1440×2880 (2:1) | Telefon ekran görüntüleri |

- `*.svg` dosyaları ikon ve feature graphic'in düzenlenebilir kaynaklarıdır;
  PNG'ler bunlardan `@resvg/resvg-js` ile render edildi. Renkler uygulamanın
  accent paletinden (`#5555dc`, `src/styles.css`'teki `--ui-accent`'in hex karşılığı).
- Ekran görüntüleri, İtalyan restoranı örnek verisi yüklü gerçek uygulamadan
  (Android emülatörü, 1440×2880'e sabitlenmiş ekran + temiz demo status bar)
  alındı. Play'in "en uzun kenar ≤ kısa kenarın 2 katı" kuralına uyar.
