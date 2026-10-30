# ringvio.se

Statisk webbplats för Ringvio, publicerad med GitHub Pages.

## Publicera

1. Lägg filerna i ett GitHub-repo (t.ex. `ringvio-site`).
2. Settings → Pages → Source: *Deploy from a branch*, branch `main`, mapp `/ (root)`.
3. Filen `CNAME` pekar sidan till `ringvio.se`.

## DNS hos one.com

Peka domänen mot GitHub Pages:

- A-poster för `ringvio.se`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- CNAME för `www`: `<github-användarnamn>.github.io`

Mejlen (MX-poster) ligger kvar hos one.com och påverkas inte.

När DNS slagit igenom: kryssa i *Enforce HTTPS* under Settings → Pages.
