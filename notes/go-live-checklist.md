# Go-Live Checklist

- [ ] Set `baseURL` in `config/_default/hugo.toml` to final `https://DOMAIN/`
- [ ] `rm -rf public resources && hugo --minify`
- [ ] Verify `public/robots.txt` has `Sitemap: https://DOMAIN/sitemap.xml`
- [ ] Verify `public/sitemap.xml` `<loc>` uses `DOMAIN`
- [ ] Verify canonical on `/start-here/` uses `DOMAIN`
- [ ] Deploy
- [ ] In Google Search Console:
  - [ ] Add Domain property
  - [ ] Verify via DNS TXT
  - [ ] Submit sitemap: `/sitemap.xml`
- [ ] Recheck indexing: URL Inspection for `/start-here/`
