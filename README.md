🎥 BPFAM-VIDEO UFFICIALI 💎

Benvenuto nel repository ufficiale del sito video BPFAM —
progetto dedicato ai contenuti multimediali con effetti luminosi, led e stile BPFAM Official.

⸻

🔹 Struttura del progetto

Video-bpfam/
├── index.html → Pagina principale con effetti led
├── style.css → Stile grafico personalizzato BPFAM
├── videos/ → Cartella con i video organizzati per categoria
│ ├── hash/ → Video hash 🇺🇸🇲🇦
│ └── weed/ → Video weed 🇺🇸🇪🇸🇳🇱🇹🇭
└── .github/
  └── workflows/
   ├── backup.yml → Backup automatico giornaliero
   └── restore.yml → Ripristino rapido del sito

⸻

🔐 1️⃣ Sicurezza e Backup automatico

Ogni giorno alle 03:00 UTC, GitHub Actions esegue un backup completo del sito.
Il backup viene salvato in due modi:
	•	come Artifact (interno a GitHub Actions)
	•	e come Release scaricabile direttamente

🗂 File collegato:
/.github/workflows/backup.yml

📦 Controlla lo stato su Actions → Backup site ZIP

oppure clicca il pulsante qui sotto per aprire direttamente la sezione dei backup:

🟣 Apri Backup su GitHub Actions

⸻

♻️ 2️⃣ Ripristino rapido (Restore workflow)

Se il sito viene segnalato o cancellato:

1️⃣ Vai in Actions
2️⃣ Seleziona Restore website from ZIP
3️⃣ Premi Run workflow

☑️ Il sistema scaricherà automaticamente l’ultimo backup .zip
e ripristinerà tutto su GitHub Pages.

🧩 File collegato:
/.github/workflows/restore.yml

⸻

🌐 3️⃣ Pubblicazione online

Il sito è pubblicato automaticamente con GitHub Pages
al seguente indirizzo:

👉 https://bpfam.github.io/Video-bpfam/

Tutto ciò che si trova nella cartella videos/ e nel file index.html viene caricato online dopo ogni commit.

⸻

💡 4️⃣ Come aggiungere nuovi video

1️⃣ Carica i tuoi file .mp4 nelle cartelle:
	•	videos/hash/
	•	videos/weed/

2️⃣ Aggiorna i nomi nei tag <video> dentro index.html
3️⃣ Premi “Commit changes”

Entro pochi secondi i nuovi video saranno visibili online 🎬

⸻

💎 5️⃣ Stile e Identità
	•	Effetti led e luminosi tipici del marchio BPFAM
	•	Colori coerenti con lo stile grafico del brand
	•	Organizzazione chiara dei contenuti
	•	Backup e Restore totalmente automatici

⸻

📅 Ultimo aggiornamento: automatico ad ogni commit
🔧 Backup automatico: ogni giorno alle 03:00 UTC
🧱 Sistema: GitHub Pages + Actions
💎 Brand: BPFAM Official

⸻

© 2025 — BPFAM Official Network
Serietà • Qualità • Rispetto 💎
