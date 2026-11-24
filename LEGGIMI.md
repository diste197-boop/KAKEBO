# Kakebo – app per Android (PWA)

Cartella da pubblicare così com'è: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
I tuoi dati NON stanno in questi file: restano solo nel browser del telefono.

## 1. Pubblicarla (gratis, una volta sola, dal PC)

**GitHub Pages**
1. Crea un account su github.com e un nuovo repository **pubblico** chiamato `kakebo`.
2. "Add file" → "Upload files" e trascina i 5 file → "Commit changes".
3. Settings → Pages → Source: "Deploy from branch" → `main` / `(root)` → Save.
4. Dopo circa un minuto l'indirizzo è `https://TUO-NOME.github.io/kakebo/`.

(Alternativa senza account Git: Netlify Drop o Cloudflare Pages, trascinando la cartella.)

Il repository è pubblico, ma contiene solo il codice dell'app: nessun saldo o spesa.

## 2. Installarla sul telefono
1. Apri l'indirizzo in Chrome.
2. Menu ⋮ → **Installa app** (o "Aggiungi a schermata Home").
3. Apri l'icona **Kakebo**: al primo avvio scegli il PIN e imposta i saldi iniziali.

Usa sempre l'icona installata: i dati sono legati a quell'indirizzo.

## 3. Backup
Impostazioni → **Salva backup** → nel menu Condividi scegli **Drive**.
Per ripristinare (nuovo telefono o dati persi): Impostazioni → **Ripristina** → scegli il file.
Il backup non contiene il PIN.

## 4. Modificare l'app in futuro
Cambia `index.html` e ricaricalo su GitHub. L'app mostra la nuova versione alla riapertura successiva
(per forzarla subito, cambia `kakebo-v1` in `kakebo-v2` dentro `sw.js`).
