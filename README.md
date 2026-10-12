# Quixotic Pursuits

https://quixotic.bharathpalavalli.com: a cabinet of curiosities (ham radio, art, games and other
experiments) by Bharath M. Palavalli.

- `index.html`: the landing page, styled by bharathpalavalli.com's own stylesheet.
- Experiments publish their sites to their own branch here (`qrpickle-site` from
  [bmp/QRPickle](https://github.com/bmp/QRPickle)'s release workflow, one force-pushed commit), and
  `.github/workflows/pages.yml` serves them under `/<Name>/`.

Setup: Settings → Pages → Source "GitHub Actions"; custom domain `quixotic.bharathpalavalli.com`
(DNS: `CNAME quixotic → bmp.github.io`), Enforce HTTPS.
