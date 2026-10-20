# Website — radialcons.ro

Site-ul trebuie să facă două lucruri: să arate lucrările ca într-o galerie și să transforme vizitatorul într-o cerere de ofertă.

## Structura recomandată

| Pagină | Conținut |
| --- | --- |
| **Acasă** | Hero pe fundal Negru Atelier cu o fotografie mare a unei piese, titlu „Atelier mic. Precizie de oțel.", subtext de un rând, buton „Cere o ofertă". Apoi: ce facem (3–4 categorii), lucrări alese, procesul în 4 pași, de ce noi, contact. |
| **Lucrări / Portofoliu** | Grilă de proiecte filtrabilă după cele 4 linii: Mobilier și vetre de foc · Structuri metalice (hale, fotovoltaic) · Producție la comandă · plus Fier forjat. Fiecare proiect: 3–8 poze, 2–3 rânduri (ce, material, finisaj, unde). |
| **Servicii** | O secțiune per linie, în ordinea din video: Mobilier și vetre de foc → Structuri metalice → Producție la comandă (cu încărcare de fișiere DXF/STEP) → Tehnologie (laser, sudură laser, plasmă, îndoire CNC). |
| **Despre noi** | Din 1999, atelierul din Târgoviște, echipa, procesul, echipamente `[DE COMPLETAT]`. |
| **Cere o ofertă** | Formularul din „Oferte → B", cu încărcare de fișiere. |
| **Contact** | Telefon, email, adresă, hartă, program `[DE COMPLETAT]`. |

## Reguli vizuale

- **Hero și benzile de impact:** Negru Atelier, text alb, accent auriu. **Restul paginilor:** alb, cu benzi alternative pe Crem.
- **Container** max. 1200 px; secțiuni cu 96 px spațiu vertical pe desktop, 64 px pe mobil; margini laterale 24 px pe mobil.
- **Tipografie web:**

| Element | Desktop | Mobil |
| --- | --- | --- |
| H1 (Playfair Display 700) | 56 px / 1,1 | 36 px |
| H2 (Playfair Display 600) | 36 px / 1,2 | 28 px |
| H3 (Montserrat 600) | 20 px | 18 px |
| Text (Montserrat 400) | 17 px / 1,6 | 16 px |
| Etichete (Montserrat 600, MAJUSCULE, +18%) | 12 px | 12 px |

- **Buton principal:** fundal Auriu `#F0A038`, text Negru Atelier, Montserrat SemiBold 15 px, MAJUSCULE, padding 14 × 28 px, colțuri 2 px. Pe fundal alb: fundal Bronz închis `#8A5220`, text alb.
- **Buton secundar:** contur 1 px în culoarea textului, fundal transparent.
- **Linkuri:** Bronz închis pe alb, Auriu pe negru; subliniere la hover.
- **Imagini:** colțuri drepte, raport 4:5 pentru lucrări, 16:9 pentru bannere; mereu cu text alternativ descriptiv („Scaune de bar din inox lustruit oglindă, restaurant").
- **Fără:** carusele automate, animații care se mișcă singure, pop-up-uri la intrare, iconițe colorate multicolor.

## Texte și SEO

- Titlul paginii: „Radial Cons – Confecții metalice la comandă din inox și aluminiu | Târgoviște"
- Descriere: „Atelier de confecții metalice din 1999: mobilier din inox și aluminiu, piese decorative, structuri metalice și fier forjat, la comandă. Proiectare, execuție, finisaj și montaj."
- Cuvinte cheie de urmărit natural în texte: confecții metalice la comandă, mobilier inox, mobilier HoReCa, scaune bar inox, structuri metalice Târgoviște, fier forjat Dâmbovița, balustrade inox.
- Buton de WhatsApp/telefon fix pe mobil (0744 704 446).

## Variabile CSS (copiază în proiect)

```css
:root {
  --rc-negru: #121110;   --rc-grafit: #23201D;
  --rc-auriu: #F0A038;   --rc-bronz: #B8712A;   --rc-bronz-inchis: #8A5220;
  --rc-otel: #A9AEB3;    --rc-crem: #F8F4E8;    --rc-alb: #FFFFFF;
  --rc-text: #1C1814;    --rc-text-2: #5E5650;  --rc-linie: #E4DCCB;
  --rc-font-titlu: "Playfair Display", Georgia, serif;
  --rc-font-text: Montserrat, "Helvetica Neue", Arial, sans-serif;
}
```

Fonturi: `https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&family=Playfair+Display:wght@600;700&display=swap`
