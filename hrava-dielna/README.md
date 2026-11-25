# Hravá dielňa

Aplikácia na tvorbu hravých úloh pre materské a základné školy, bez programovania:
kvízy, tajničky, pexeso, priraďovanie, doplňovačky, osemsmerovky, zoraďovanie,
triedenie, prešmyčky a pravda/nepravda.

## Spustenie

- **Na webe:** po zapnutí GitHub Pages na adrese
  `https://daubner5696.github.io/School/hrava-dielna/`
- **Bez internetu:** stiahnite `index.html` a otvorte ho v prehliadači.

## Zapnutie GitHub Pages (raz)

Settings → Pages → Build and deployment → Source: *Deploy from a branch* →
Branch: `main`, priečinok `/ (root)` → Save. Asi o minútu bude stránka dostupná.

## Ukladanie úloh na GitHub

V aplikácii kliknite na **☁ Pripojiť GitHub** a postupujte podľa návodu (vytvorenie tokenu
s právom *Contents: Read and write* len pre tento repozitár). Potom sa každá upravená
úloha sama uloží do priečinka `hrava-dielna/ulohy/` ako súbor `.json`.

Pri každej uloženej úlohe nájdete v ponuke **⋯** položku **🔗 Kopírovať odkaz pre deti**.
Odkaz má tvar `…/hrava-dielna/#hraj-<id>` a otvorí úlohu iba na hranie.

Token sa ukladá iba v prehliadači, v ktorom ste ho zadali. Na spoločných počítačoch ho nezadávajte.
