# Araz VinÃ§ â€” Web Sitesi

Salihli ve Ã§evresinde Hiab & Mobil vinÃ§ kiralama hizmeti iÃ§in kurumsal web sitesi.

## ğŸ—ï¸ Teknoloji

- **Pure HTML/CSS/JS** â€” herhangi bir framework yok
- **Static deploy** â€” Render.com Ã¼zerinden Ã¼cretsiz host

## ğŸš€ Deploy (Render.com)

1. [render.com](https://render.com) â†’ New â†’ Static Site
2. GitHub repo'yu baÄŸla: `hknraz-blip/ara`
3. Build command: `empty` (yok)
4. Publish directory: `/`
5. **Custom domain:** `arazvincsalihli.com` â†’ DNS'de `CNAME` â†’ `full://ara.onrender.com`

## ğŸ“ Dizin YapÄ±sÄ±

```
/
â””â”€â”€ index.html   â† TÃ¼m site tek dosyada
```

## âš ï¸ DÃ¼zenlenecek Bilgiler

- **Telefon numaralarÄ±:** `index.html` iÃ§inde `0532 123 45 67` â†’ gerÃ§ek numara
- **E-posta:** `info@arazvincsalihli.com` â†’ gerÃ§ek adres
- **Form:** `formspree.io/f/XXXXX` â†’ gerÃ§ek Formspree ID al (Ã¼cretsiz)
- **Alan chip'leri:** Hizmet bÃ¶lgeleri gÃ¼ncellenebilir

## ğŸ”„ GÃ¼ncelleme

```bash
git add .
git commit -m "update"
git push
```

Render otomatik yeniden deploy eder.
