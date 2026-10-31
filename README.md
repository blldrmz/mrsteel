# MR Steel — mrsteel

Tek sayfalık, 4 dilli (TR / EN / RU / KA) çelik konstrüksiyon sitesi. Saf HTML/CSS/JS — kurulum gerekmez.

## Yapı
- `index.html` — tüm site (metinler `I18N` nesnesinde)
- `assets/` — logo ve favicon

## Referans projesi eklemek
1. Fotoğrafı `assets/projects/` klasörüne `p19.jpg` (büyük) ve `p19-t.jpg` (küçük) olarak koyun.
2. `index.html` içindeki `REFERENCES` listesine `["p19",{tr:"…",en:"…",ru:"…",ka:"…"}]` satırını ekleyin.

## Yayın
GitHub → Settings → Pages → Branch: `main` / root. Custom domain: `mrsteel.ge` (CNAME dosyası). DNS: `A @` → 185.199.108.153 / .109.153 / .110.153 / .111.153, `CNAME www` → blldrmz.github.io
Dil linkleri: `?lang=tr`, `?lang=en`, `?lang=ru`, `?lang=ka`.
