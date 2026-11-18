# 🪔 Shubh Vivah — Ram Akshayver & Savita

A digital wedding invitation for the wedding of **Ram Akshayver & Savita** on **Wednesday, 2 December 2026**.

**Open the invitation:** https://ramakshayverpal.github.io/ram-savita-wedding/

#RaSaForever

---

## Celebrations

| Event | Date | Time | Place |
|---|---|---|---|
| Haldi & Mehandi | Tuesday, 1 December 2026 | | |
| Baraat Departure | Wednesday, 2 December 2026 | 9:00 AM | Vaidaha, Sultanpur |
| Wedding Ceremony | Wednesday, 2 December 2026 | | Lal Singh Palace, Lahar, Bhind |
| Reception Dinner | Saturday, 5 December 2026 | 7:00 PM | Vaidaha, Sultanpur |

---

## Editing

Everything you see on the page (names, events, venues, map links, QR codes, music) comes from one
JSON block near the top of `<body>` in `index.html`:

```html
<script id="wedding-config" type="application/json"> … </script>
```

Edit the text there and refresh the page. Link-preview text (WhatsApp, etc.) is in the `<meta>` tags
in `<head>`, and the preview picture is `og-image.jpg` (1200 × 630).

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Files

| File | Used for |
|---|---|
| `index.html` | The whole invitation (layout, styles, script and content) |
| `monogram-red.png`, `monogram-gold.png` | R&S monogram |
| `home-qr.png`, `wedding-venue-qr.png` | Directions QR codes on the venue cards |
| `og-image.jpg` | Link-preview image |
| `image1.jpg`, `desktop_arti.webm`, `mobile_arti.webm` | Intro illustration and opening video |
| `ganesh_mantra.mp3`, `wedding_song.mp3` | Background music |

---

Built on an open-source wedding-invitation template (MIT License, see `LICENSE`).

*॥ Shubhamastu ॥*
