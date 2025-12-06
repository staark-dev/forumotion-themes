# 🎨 Teme Forumotion de la staark-dev

## ✨ Descriere

Acest depozit conține o colecție de teme (skin-uri) **gratuite** și **moderne** create special pentru platforma de forumuri **Forumotion**. Fiecare temă este concepută pentru a oferi un aspect proaspăt, o experiență de utilizare îmbunătățită și o compatibilitate excelentă cu diverse dispozitive (design responsiv).

Scopul nostru este de a oferi comunităților Forumotion opțiuni estetice de înaltă calitate, ușor de instalat și personalizat.

## 📁 Structura Depozitului

Fiecare temă este organizată în propriul director. În mod tipic, un director de temă va conține:
* `styles.css` (sau fișierul principal CSS)
* `template.html` (sau modificări la template-urile de bază)
* `scripts.js` (scripturi adiționale, dacă există)
* `screenshots/` (capturi de ecran)

## 🎭 Teme Disponibile

| Tema | Stare | Descriere Scurtă |
| :--- | :---: | :--- |
| **Aether** | ✅ Stabil | O temă minimalistă, bazată pe un fundal întunecat (dark mode), ideală pentru comunitățile de gaming sau tehnologie. |
| **Luminos** | 🛠️ Beta | Un design curat, bazat pe culori deschise și mult spațiu alb. Perfectă pentru comunități axate pe artă sau lifestyle. |
| **RetroWave** | ✅ Stabil | Inspirată de estetica anilor '80, cu nuanțe de neon și fonturi pixelate. O temă tematică și îndrăzneață. |
| **[Numele Următoarei Teme]** | 💡 În lucru | *O scurtă descriere a viitorului proiect.* |

### Previzualizare

Pentru a vedea temele în acțiune, vizitați pagina noastră de demonstrație:
[Demo Live Aether](https://demo.exemplu.com/aether)
[Demo Live RetroWave](https://demo.exemplu.com/retrowave)

## 🚀 Instalare și Utilizare

Instalarea temelor noastre este un proces simplu și rapid.

### Pasul 1: Selectați Tema
Navigați în directorul temei dorite (de ex. `/Aether`).

### Pasul 2: Copiați Codul
1.  Deschideți fișierul **`styles.css`**.
2.  Copiați întregul conținut.

### Pasul 3: Aplicați în Panoul de Administrare Forumotion
1.  Intrați în Panoul de Administrare (PCA) al forumului dumneavoastră.
2.  Navigați la **Afișare > Imagini și Culori > CSS**.
3.  Lipiți conținutul copiat de la Pasul 2 în câmpul de text al foii de stil.
4.  Salvați modificările.

### Pasul 4: Modificări HTML (Dacă este Necesar)
Unele teme necesită modificări la template-urile forumului (de exemplu, adăugarea unor containere custom).
* Verificați fișierul **`instructions.md`** din directorul temei respective pentru pașii suplimentari.

## 🛠️ Personalizare

Toate temele folosesc variabile CSS (Custom Properties) pentru culori și fonturi, făcând personalizarea foarte ușoară:

```css
/* Exemplu de personalizare în CSS-ul temei */
:root {
  --main-color: #3498db; /* Culoarea primară */
  --text-color: #f0f0f0;  /* Culoarea textului */
  --font-family: 'Roboto', sans-serif;
}
```
## 🤝 Contribuții
Orice contribuție este extrem de apreciată! Fie că este vorba de raportarea unui bug, de sugestii de funcționalități sau de îmbunătățirea codului existent, vă rugăm să urmați acești pași:

Faceți un Fork al depozitului.

Creați o ramură nouă (git checkout -b feature/nume_nou).

Trimiteți modificările (git commit -am 'Adaugă o funcționalitate noua...').

Împingeți (push) ramura (git push origin feature/nume_nou).

Deschideți un Pull Request (PR).

## 📄 Licență
Acest proiect este licențiat sub licența MIT.

Sunteți liber(ă) să folosiți, să modificați și să distribuiți temele, cu condiția să includeți nota de copyright și permisiunea specificată în Licență.

© 2024 staark-dev
