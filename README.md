# FATheme Manager

Un manager modern de teme pentru **Forumotion**, creat pentru administratori care doresc să instaleze, configureze și gestioneze teme personalizate într-un mod profesionist și sigur, direct din panoul de administrare.

FATheme Manager integrează un UI avansat în ACP Forumotion, fără a altera experiența utilizatorilor obișnuiți ai forumului.

## 🚀 Funcționalități principale

### 📦 Catalog de teme
- Încărcare automată a temelor dintr-un index JSON.
- Afișare profesională în stil ACP.
- Prezentare detaliată: versiune, autor, changelog, screenshot, compatibilitate etc.

### 🔍 Pagini dedicate
- **Details** — informații complete despre temă.
- **Preview** — previzualizare live.
- **Install** — instalare asistată cu log în timp real.
- **Config** — configurare avansată după instalare.

### 🛠 Installer inteligent
- Verificare compatibilitate engine (phpBB2/3, Invision, ModernBB, AwesomeBB).
- Detectarea template-urilor editate existente.
- Sistem opțional de **backup** pentru template-uri.
- Mesaje log structurate (OK / Warning / Error).
- Anulare instalare și revenire la paginile anterioare.

### 🧩 Suport pentru plugin-uri
- Temele pot include extensii (widgets / plugins).
- Activare / dezactivare direct din Config.

### 🗄 Cache intern
- Cache pentru manifest și index.
- Invalidare automată după un anumit timp.

### 🧭 Router intern
- Navigare tip **single-page** între: Catalog → Details → Install → Config.
- Breadcrumb dinamic.
- Reține ultima pagină la refresh.

## 🛡 Permisiuni necesare

Extensia folosește doar permisiuni minime:

- `activeTab` — necesar pentru citirea datelor din ACP
- `storage` — cache local și salvarea stării temei instalate
- `scripting` — pentru a injecta UI în ACP
- `https://raw.githubusercontent.com/*` — încărcarea manifestelor temelor

⚠️ Extensia **nu colectează date personale** și nu transmite informații externe.

## 🔧 Pentru dezvoltatori

### Componente principale
- **bootstrap.js** — încarcă modulele și inițiază aplicația.
- **System** — verifică engine-ul forumului, template-urile editate și gestionează backup-urile.
- **Theme** — controlează paginile dedicate unei teme.
- **Installer** — afișează procesul de instalare, log, butoane, erori etc.
- **Router** — controlează navigarea în stil single-page.
- **UI** — efecte vizuale, animații, breadcrumb.

### Helpers importanți
- `findTheme(id)`
- `findInstalledTheme()`
- `isThemeInstalledLocally()`
- `parseTemplateMark()`

## 📝 TODO

- [ ] Sistem de update pentru temele instalate
- [ ] Upload custom theme (în afara catalogului)
- [ ] Editor CSS cu preview live
- [ ] Management avansat pentru plugin-uri
- [ ] Restaurare automată a backup-ului
- [ ] Logging într-un fișier local

## 📜 Licență

FATheme Manager este distribuit sub licența **MIT**.
Puteți folosi, modifica și redistribui proiectul liber.
