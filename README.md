# Manka Fejlesztő Kuckó – főoldal

A **„Minden kis lépés számít”** koncepció alapján elkészült reszponzív, statikus weboldal prototípusa.

## Tartalom

- `site/index.html` – teljes főoldal egy fájlban (HTML, CSS, JavaScript)
- `site/assets/images/` – saját fotók helye
- `.github/workflows/pages.yml` – automatikus GitHub Pages közzététel minden `main` ágra érkező változásnál
- `site/robots.txt` – keresőrobotok kizárása a tesztidőszakban

## Publikálás GitHub Pages-szel

1. Hozz létre egy **public** repositoryt `manka` néven.
2. Töltsd fel a fájlokat a repository gyökerébe, vagy kérd a ChatGPT-t, hogy a csatlakoztatott GitHub-fiókba feltöltse őket.
3. A repository **Settings > Pages > Build and deployment** alatt a **Source** mezőnél válaszd a **GitHub Actions** lehetőséget.
4. A `main` ágra való feltöltés elindítja a `Manka weboldal - GitHub Pages` workflow-t az **Actions** fülön.
5. A GitHub Pages megadja a publikált URL-t; várható alakja `https://levente-eng.github.io/manka/`, de csak a GitHub által ténylegesen kiadott linkre hagyatkozz.

## Saját képek

A két elsődleges fotó neve:

- `site/assets/images/manka-fooldal.webp`
- `site/assets/images/manka-csapat.webp`

A helyük automatikusan működik, amint a fájlok a repositoryba kerülnek. A fotók eredeti Drive-mappája:
https://drive.google.com/drive/u/0/folders/16BvpiP4Y4kHvscti4uGB2r5cDPahPLzb

## Állapot és korlátok

**Ez még koncepció és tesztoldal, nem éles megrendelésfelvevő rendszer.**

- Az érdeklődési űrlap csak az alapértelmezett e-mail alkalmazást nyitja meg (`mailto:`). Nem küld szerverre és nem tárol adatokat.
- Az oldal szándékosan `noindex` jelöléssel és `robots.txt` tiltással készült, hogy a tesztverzió ne jelenjen meg a keresőkben. Élesítéskor ezeket felül kell vizsgálni és módosítani.
- A kapcsolati adatok, szolgáltatási leírások, helyszín, személyek és képek ügyfél-oldali véglegesítést igényelnek.
- Publikálás előtt szükséges az adatkezelési / impresszum információk és a gyermekeket ábrázoló fotók felhasználási jogosultságainak ellenőrzése.
- A jelenlegi oldalon nincsenek nyomkövetők vagy sütit igénylő analitikai eszközök. Külső Google Fonts betöltés történik.