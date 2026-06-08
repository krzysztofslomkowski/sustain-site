# Sustain site

Statyczna strona landing page projektu Sustain.

Adres docelowy:

```txt
https://sustain.empiremusic.pl
```

Repo jest przygotowane pod GitHub Pages.

## Publikacja

1. W GitHub wejdź w `Settings -> Pages`.
2. Ustaw `Deploy from a branch`.
3. Branch: `main`.
4. Folder: `/root`.
5. Zapisz.

## DNS

Dla domeny `empiremusic.pl` dodaj rekord:

```txt
Type: CNAME
Host: sustain
Value: krzysztofslomkowski.github.io
```

Potem w GitHub Pages ustaw custom domain:

```txt
sustain.empiremusic.pl
```
