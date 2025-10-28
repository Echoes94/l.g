README.md

```markdown
# 🔮 L.G. - Metodo EFO® Website

**Autorealizzazione e Felicità Esistenzialista**

Sito web professionale per Gabriele Lucesole - Coach Professionista specializzato in trasformazione esistenziale attraverso il Metodo EFO®.

---

## 📋 Indice

- [Caratteristiche](#caratteristiche)
- [Struttura del Progetto](#struttura-del-progetto)
- [Installazione](#installazione)
- [Configurazione GitHub Pages](#configurazione-github-pages)
- [Personalizzazione](#personalizzazione)
- [Tecnologie Utilizzate](#tecnologie-utilizzate)
- [Browser Supportati](#browser-supportati)
- [Licenza](#licenza)

---

## ✨ Caratteristiche

- **Design Responsive**: Ottimizzato per desktop, tablet e mobile
- **Motion ID**: Animazioni fluide con dissolvenze e glow effects
- **Palette Profonda**: Colori visionari blu/viola (#170B3B, #341948, #0000FF)
- **Typography System**: Playfair Display, Merriweather, Inter
- **SEO Optimized**: Meta tags, Open Graph, struttura semantica
- **Performance**: Lazy loading, animazioni ottimizzate, codice pulito
- **Accessibilità**: ARIA labels, reduced motion support, alto contrasto

---

## 📁 Struttura del Progetto

```
elle.gi/
├── index.html              # Homepage
├── chi-sono.html           # Pagina "Chi sono"
├── metodo-efo.html         # Pagina "Metodo EFO®"
├── css/
│   ├── main.css            # Stili principali
│   ├── animations.css      # Animazioni Motion ID
│   └── responsive.css      # Media queries
├── js/
│   └── main.js             # JavaScript interazioni
├── images/
│   └── gabriele.jpg        # Foto personale
└── README.md               # Questo file
```

---

## 🚀 Installazione

### Prerequisiti

- Account GitHub
- Git installato sul tuo computer (opzionale, puoi usare l'interfaccia web)

### Metodo 1: Caricamento tramite Interfaccia Web GitHub (CONSIGLIATO per principianti)

#### Passo 1: Prepara i File

1. Crea una cartella sul tuo computer chiamata `elle.gi`
2. Copia tutti i file HTML nella cartella principale
3. Crea le sottocartelle: `css`, `js`, `images`
4. Copia i file CSS nella cartella `css`
5. Copia il file JavaScript nella cartella `js`
6. Copia la tua foto nella cartella `images` e rinominala `gabriele.jpg`

#### Passo 2: Accedi a GitHub

1. Vai su [github.com](https://github.com)
2. Fai login con il tuo account
3. Vai al tuo repository `elle.gi`

#### Passo 3: Carica i File

1. Clicca sul pulsante **"Add file"** → **"Upload files"**
2. Trascina tutti i file e le cartelle nella finestra di upload
3. Scrivi un messaggio di commit (es. "Initial website upload")
4. Clicca su **"Commit changes"**

⚠️ **IMPORTANTE**: Assicurati di mantenere la struttura delle cartelle quando carichi i file!

#### Passo 4: Verifica la Struttura

Dopo il caricamento, il tuo repository dovrebbe apparire così:

```
elle.gi/
├── index.html
├── chi-sono.html
├── metodo-efo.html
├── css/
│   ├── main.css
│   ├── animations.css
│   └── responsive.css
├── js/
│   └── main.js
├── images/
│   └── gabriele.jpg
└── README.md
```

---

### Metodo 2: Caricamento tramite Git (per utenti avanzati)

```bash
# 1. Clona il repository
git clone https://github.com/[tuo-username]/elle.gi.git
cd elle.gi

# 2. Copia tutti i file nella cartella

# 3. Aggiungi i file a Git
git add .

# 4. Crea un commit
git commit -m "Initial website upload"

# 5. Carica su GitHub
git push origin main
```

---

## 🌐 Configurazione GitHub Pages

### Passo 1: Attiva GitHub Pages

1. Vai al tuo repository su GitHub
2. Clicca su **"Settings"** (Impostazioni)
3. Nel menu laterale, clicca su **"Pages"**
4. Nella sezione **"Source"**:
   - Seleziona **"Deploy from a branch"**
   - Branch: **"main"**
   - Folder: **"/ (root)"**
5. Clicca su **"Save"**

### Passo 2: Attendi la Pubblicazione

- GitHub impiegherà 2-5 minuti per pubblicare il sito
- Vedrai un messaggio verde con l'URL del tuo sito
- L'URL sarà: `https://[tuo-username].github.io/elle.gi`

### Passo 3: Verifica il Sito

1. Clicca sull'URL fornito da GitHub
2. Verifica che tutte le pagine funzionino correttamente
3. Controlla che le immagini siano caricate
4. Testa la navigazione su mobile

---

## 🎨 Personalizzazione

### Aggiungere la Tua Foto

1. Prepara una foto in formato JPG (consigliato: 800x800px)
2. Rinominala `gabriele.jpg`
3. Caricala nella cartella `images/` del repository
4. Sostituisci il file esistente

**Opzioni di Upload:**
- **Via Web**: Settings → Pages → Upload nella cartella `images`
- **Via Git**: Copia il file nella cartella locale e fai commit/push

### Modificare i Colori

Apri `css/main.css` e modifica le variabili CSS:

```css
:root {
    --color-bg-primary: #0E050F;        /* Sfondo principale */
    --color-accent-primary: #341948;    /* Accento viola */
    --color-accent-electric: #0000FF;   /* Blu elettrico */
    --color-text-light: #D4F1F4;        /* Testo chiaro */
}
```

### Modificare i Testi

1. Apri i file HTML con un editor di testo
2. Cerca il testo che vuoi modificare
3. Modificalo mantenendo i tag HTML
4. Salva e carica su GitHub

### Aggiungere Google Analytics (Opzionale)

Aggiungi questo codice prima del tag `</head>` in ogni file HTML:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TUO-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TUO-ID');
</script>
```

---

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura semantica
- **CSS3**: Styling avanzato con variabili CSS
- **JavaScript (Vanilla)**: Interazioni senza librerie esterne
- **Google Fonts**: Playfair Display, Merriweather, Inter
- **GitHub Pages**: Hosting gratuito

---

## 🌍 Browser Supportati

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+
- ⚠️ Internet Explorer: Non supportato

---

## 📱 Test Responsiveness

Il sito è ottimizzato per:
- 📱 Mobile: 320px - 767px
- 📱 Tablet: 768px - 1024px
- 💻 Desktop: 1025px+

**Come testare:**
1. Apri il sito nel browser
2. Premi `F12` per aprire Developer Tools
3. Clicca sull'icona del dispositivo mobile
4. Seleziona diversi dispositivi dal menu

---

## 🐛 Risoluzione Problemi

### Il sito non si carica

**Causa**: GitHub Pages non è attivato
**Soluzione**: Vai su Settings → Pages e attiva la pubblicazione

### Le immagini non si vedono

**Causa**: Path errato o nome file sbagliato
**Soluzione**: 
- Verifica che il file sia in `images/gabriele.jpg`
- Controlla che il nome sia esattamente `gabriele.jpg` (minuscolo)

### I CSS non funzionano

**Causa**: File CSS non caricati o path errato
**Soluzione**:
- Verifica la struttura delle cartelle
- Controlla che i file CSS siano in `css/`
- Verifica i link nel tag `<head>` dei file HTML

### Il menu mobile non funziona

**Causa**: JavaScript non caricato
**Soluzione**:
- Verifica che `main.js` sia in `js/`
- Controlla il link prima del tag `</body>`
- Apri la console del browser (F12) per vedere errori

---

## 🔄 Aggiornamenti Futuri

Per aggiornare il sito:

1. Modifica i file localmente
2. Carica i file modificati su GitHub
3. GitHub Pages aggiornerà automaticamente il sito (2-5 minuti)

**Via Web:**
- Vai al file su GitHub
- Clicca sull'icona della matita (Edit)
- Modifica il contenuto
- Clicca su "Commit changes"

**Via Git:**
```bash
git add .
git commit -m "Descrizione modifiche"
git push origin main
```

---

## 📞 Supporto

Per problemi tecnici o domande:

- 📧 Email: gabriele.lucesole@gmail.com
- 📱 Instagram: [@gabrielelucesole](https://instagram.com/gabrielelucesole)
- 💼 LinkedIn: [gabrielelucesole](https://linkedin.com/in/gabrielelucesole)

---

## 📝 Checklist Pre-Pubblicazione

Prima di pubblicare il sito, verifica:

- [ ] Tutti i file HTML sono caricati
- [ ] Tutti i file CSS sono nella cartella `css/`
- [ ] Il file JavaScript è nella cartella `js/`
- [ ] La foto è caricata in `images/gabriele.jpg`
- [ ] I link di navigazione funzionano
- [ ] L'email è corretta in tutti i link `mailto:`
- [ ] I link social sono corretti
- [ ] GitHub Pages è attivato
- [ ] Il sito è accessibile all'URL pubblico
- [ ] Test su mobile completato
- [ ] Test su desktop completato

---

## 🎯 Prossimi Passi Consigliati

1. **Dominio Personalizzato** (Opzionale)
   - Acquista un dominio (es. `gabrielelucesole.com`)
   - Configura il DNS per puntare a GitHub Pages
   - Aggiungi il dominio nelle impostazioni di GitHub Pages

2. **SEO**
   - Registra il sito su Google Search Console
   - Crea una sitemap.xml
   - Ottimizza i meta tag per ogni pagina

3. **Analytics**
   - Integra Google Analytics
   - Monitora le visite e il comportamento degli utenti

4. **Performance**
   - Comprimi le immagini (usa TinyPNG)
   - Minimizza CSS e JavaScript (per versioni future)

---

## 📄 Licenza

© 2025 Gabriele Lucesole. Tutti i diritti riservati.

Questo sito web e tutti i suoi contenuti sono proprietà di Gabriele Lucesole.
Il Metodo EFO® è un marchio registrato.

---

## 🙏 Ringraziamenti

Sito web sviluppato con:
- ❤️ Passione
- 🧠 Intelligenza
- ✨ Visione

**"Solo la verità che edifica è verità per te."** — Søren Kierkegaard

---

## 📚 Risorse Utili

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

**Versione**: 1.0.0  
**Ultimo Aggiornamento**: Ottobre 2025  
**Contatto**: gabriele.lucesole@gmail.com

🔮 **L.G. - Metodo EFO®** | Autorealizzazione e Felicità Esistenzialista
```

---

## 🎉 COMPLETAMENTO PROGETTO

Perfetto! Tutti i file sono stati creati. Ecco il riepilogo completo:

### ✅ File Creati:

1. **index.html** - Homepage completa
2. **chi-sono.html** - Storia in 5 atti
3. **metodo-efo.html** - Landing page Metodo EFO®
4. **css/main.css** - Stili principali (3 parti)
5. **css/animations.css** - Motion ID completo
6. **css/responsive.css** - Design responsive
7. **js/main.js** - JavaScript interazioni
8. **README.md** - Guida completa

### 📦 Cosa Fare Ora:

1. **Copia tutti i file** in una cartella sul tuo computer
2. **Aggiungi la tua foto** nella cartella `images/` come `gabriele.jpg`
3. **Carica tutto su GitHub** seguendo le istruzioni nel README
4. **Attiva GitHub Pages** nelle impostazioni del repository
5. **Testa il sito** all'URL fornito da GitHub

### 🎯 URL del Sito:
Sarà disponibile a: `https://[tuo-username].github.io/elle.gi`

Vuoi che ti guidi passo-passo nel caricamento su GitHub o hai domande? 🚀
