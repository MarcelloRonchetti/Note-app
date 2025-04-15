Note App – React Challenge
Questa è un'applicazione semplice ma completa per la gestione di note personali. L'app permette di creare, modificare, eliminare e cercare note, con salvataggio persistente tramite localStorage.

Funzionalità principali
CRUD completo: aggiunta, modifica e cancellazione delle note
Ricerca dinamica: per titolo e contenuto
Categorie e filtri: per tipo di nota e priorità
Responsive design: ottimizzato per dispositivi mobili e desktop
Navigazione a più pagine: con React Router
Styling moderno: con styled-components (CSS-in-JS)
Tecnologie utilizzate
React
React Router
Context API + useReducer
styled-components
localStorage API
Struttura del progetto
bash
Copia
Modifica
src/
├── components/     # Componenti riutilizzabili e specifici
├── context/        # Gestione dello stato globale con Context API
├── hooks/          # Custom hooks (es. useLocalStorage)
├── pages/          # Componenti principali per il routing
├── utils/          # Funzioni di utilità (filtri, ordinamenti, ecc.)
├── App.js
└── index.js
Installazione e avvio
Clona il repository:

bash
Copia
Modifica
git clone https://github.com/tuo-username/note-app.git
cd note-app
Installa le dipendenze:

bash
Copia
Modifica
npm install
Avvia l'applicazione:

bash
Copia
Modifica
npm start
