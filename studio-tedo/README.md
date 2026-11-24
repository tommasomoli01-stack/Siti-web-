# Studio Tedo · sito

Sito statico (nessuna build): `index.html`, `privacy.html`, `termini.html`.
Pubblicabile così com'è su Cloudflare Pages (cartella di output: `studio-tedo`); `/privacy` e `/termini` vengono risolti in automatico.

Modulo demo: impostare `LEAD_ENDPOINT` in `index.html` (es. Cloudflare Worker o Formspree).
Se resta vuoto, l'invio apre l'app di posta con la richiesta già compilata verso informazioni.tedo@gmail.com.
