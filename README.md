# obura.io

Obura Studios web sitesi — [Astro](https://astro.build) ile kurulmuş statik site.

## Geliştirme

```bash
npm install
npm run dev
```

## İçerik güncelleme

Proje listesi tek bir dosyadan beslenir: [`src/data/projects.json`](src/data/projects.json).
Yeni bir uygulama eklemek için o dosyaya bir girdi ekleyip `main` dalına push'lamak yeterli.

Her push'ta site GitHub Actions ile derlenip GitHub Pages'e otomatik yayınlanır
([`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)).

## Alan adı

`obura.io` — DNS, Squarespace Domains üzerinde; A kayıtları GitHub Pages'e yönlenir.
