# ASUS ROG Astral GeForce RTX 5090 — 3D anatomiya

O'zbek tilidagi interaktiv maqola. Sahifani pastga aylantirganingizda video kartaning har bir qismi (GB202 protsessor, GDDR7 xotira, VRM, bug' kamerasi, radiator, to'rtta ventilyator, korpus, portlar) 3D sahnada alohida ajralib chiqadi va tushuntiriladi. Oxirida qismlarni o'zingiz tanlab ko'radigan erkin ko'rish rejimi bor.

**Sayt:** https://akhadovc.github.io/rog-astral-rtx5090/

## Fayllar

| Fayl | Nima |
| --- | --- |
| `index.html` | Sahifaning o'zi. 3D sahna [Three.js](https://github.com/mrdoob/three.js) r169 da quriladi (jsDelivr CDN orqali yuklanadi). |
| `astral-model.bin` | Veb uchun optimallashtirilgan 3D model: gzip qilingan GLB, taxminan 2,6 MB. Brauzer uni o'zi ochadi. |

Ikkala fayl bitta papkada turishi kerak. Saytni oddiy statik hostingda (GitHub Pages, Netlify) ochish mumkin; `file://` orqali to'g'ridan-to'g'ri ochilganda brauzer modelni yuklamaydi.

## Mualliflik va litsenziyalar

- **3D model:** [“Rtx 5090 ROG ASTRAL”](https://sketchfab.com/3d-models/rtx-5090-rog-astral-7d6fc3376ecc4fe095f8fa0b7605766d), muallif [Branz](https://sketchfab.com/BrDvnci), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) litsenziyasi asosida.
  O'zgartirishlar: model veb uchun soddalashtirildi (taxminan 3,1 mln uchburchakdan 290 mingtaga), qismlarga ajratildi, materiallari qayta sozlandi va har bir qism uchun ambient occlusion soyalari hisoblab qo'shildi. Bug' kamerasi, issiqlik quvurlari, termal qoplama, 16-pin ulagich va ARGB chizig'i asl modelda yo'q, ular sahifada sxematik tarzda qo'shilgan.
- **Three.js** — MIT litsenziyasi.
- Texnik ma'lumotlar manbalari sahifaning "Manbalar" bo'limida keltirilgan.
- ASUS, ROG, NVIDIA va GeForce tegishli egalarining savdo belgilaridir.
