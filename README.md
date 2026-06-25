# 📅 MS Project & ProjectLibre Juhend

> Veebileht, mis selgitab Microsoft Projecti ja ProjectLibre põhifunktsioone samm-sammult.

## Sisukord

- [Projekti kirjeldus](#projekti-kirjeldus)
- [Failid](#failid)
- [Lisatud funktsionaalsused](#lisatud-funktsionaalsused)
- [Tehtud tööd](#tehtud-tööd)
- [Kasutatavad tehnoloogiad](#kasutatavad-tehnoloogiad)
- [Pildid](#pildid)
- [Lingid](#lingid)

---

## Projekti kirjeldus

See projekt on õppeveebileht, mis õpetab kasutama **Microsoft Project** ja **ProjectLibre** tarkvara. Veebileht on loodud HTML ja CSS abil ning avaldatud GitHub Pages kaudu.

Projekt sisaldab kolme põhijuhendi:
1. Uue kalendri loomine MS Projectis
2. Arvutusvälja lisamine projekti
3. Diagrammide loomine MS Projectis ja ProjectLibre's

---

## Failid

| Fail | Kirjeldus |
|------|-----------|
| `index.html` | Kalendri loomise juhend (MS Project & ProjectLibre) |
| `diagramm.html` | Diagrammide loomise juhend |
| `style.css` | Kõigi lehtede kujundus |
| `README.md` | Projekti kirjeldus |

> [!NOTE]
> `valem.html` fail eemaldati `projectLibre` harus, kuna ProjectLibre's ei ole eraldi arvutusvälja funktsiooni.

---

## Lisatud funktsionaalsused

### Kalender (`index.html`)
- Uue kalendri loomine MS Projectis ja ProjectLibre's
- Tööpäevade ja tööaegade muutmine
- Eripäevade lisamine (puhkused jne)
- Selgitus, kuidas kalender mõjutab projekti ajakava

### Diagrammid (`diagramm.html`)
- Gantt-diagrammi kasutamine MS Projectis
- Network Diagram (sõltuvuste vaade)
- Gantt-diagramm ja ressursidiagramm ProjectLibre's
- Diagrammi eksportimine PDF-i

### Navigeerimismenüü
- Kõigil lehtedel on ühtne navigeerimismenüü
- Lingid: Kalender | Arvutusväli | Diagrammid

---

## Tehtud tööd

- [x] HTML struktuur loodud (`index.html`)
- [x] CSS kujundus lisatud (`style.css`)
- [x] Navigeerimismenüü lisatud
- [x] `valem.html` kustutatud (`projectLibre` harus)
- [x] `diagramm.html` loodud ja täiendatud ProjectLibre sisuga
- [x] `index.html` uuendatud ProjectLibre kalendri juhendiga
- [x] Issues loodud ja Kanban tahvlil hallatud
- [x] GitHub Pages avaldatud

---

## Kasutatavad tehnoloogiad

- **HTML5** — lehe struktuur
- **CSS3** — kujundus (muutujad, flexbox, responsive)
- **GitHub Pages** — veebimajutus
- **Git** — versioonihaldus

### Näidis commit-sõnum

```bash
git add .
git commit -m "Lisa diagrammide juhend ja uuenda navigeerimismenüüd (Closes #2)"
git push origin projectLibre
```

---

## Pildid

Pildid asuvad kaustas `images/`. Iga juhendi sammu juurde on lisatud ekraanipilt vastavast tegevusest programmis.

![Näide](images/samm1.png)

> [!TIP]
> Tee ekraanipildid vahetult pärast iga sammu sooritamist, et juhend oleks võimalikult täpne.

---

## Lingid

- 🌐 [Veebileht (GitHub Pages)](https://SINU-KASUTAJANIMI.github.io/REPO-NIMI/)
- 💻 [GitHub repositoorium](https://github.com/SINU-KASUTAJANIMI/REPO-NIMI)
- 📹 [Arvutusvälja video](https://www.youtube.com/watch?v=bP1Wi4wGlaw&t=367s)
- 📹 [Diagrammide video](https://www.youtube.com/watch?v=iTpoBlkR0OE)

---

> [!WARNING]
> Veendu, et kõik pildifailid on lisatud kausta `images/` enne GitHub Pages avaldamist, muidu kuvatakse tühjad kohad.

[^1]: Juhend koostatud Microsoft Project 2019 ja ProjectLibre 1.9 põhjal.
[^2]: GitHub Pages seadistamiseks mine: Settings → Pages → Source → vali haru `projectLibre`.
