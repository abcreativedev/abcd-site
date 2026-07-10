# abcd-site

Deze repo host **twee** kale statische sites.

## Structuur

```
/                 → AB Creative Dev-site (index.html + CNAME in de root)
                    live via GitHub Pages op https://abcreativedevelopment.nl/
/meshfamily/      → Mesh Family-site (bron)
                    domein: meshfamily.nl — nu geparkeerd tot Mesh "staat"
```

## Waarom zo

GitHub Pages host één site + één domein per repo. `abcd` blijft daarom in de
root en blijft live. `meshfamily/` staat hier als bron bewaard, maar wordt
(nog) niet apart gehost.

## Mesh later los tillen ("zodra mesh staat")

1. Maak een nieuwe repo `meshfamily` aan.
2. Verplaats de inhoud van `/meshfamily/` naar de root van die nieuwe repo.
3. Zet GitHub Pages aan (Deploy from branch → main → / root).
4. De `CNAME` (meshfamily.nl) staat al klaar; herpunt het domein naar de
   nieuwe repo en de site is weer live.
5. Verwijder de map `/meshfamily/` hier.
