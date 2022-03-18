# DOCUMENTAZIONE PER WEBSITE_OFFICIAL

## OBIETTIVI:

- Creazione homepage: https://preview.cruip.com/appy/ (Gabriel e Nazareno)
- Creazione About: https://preview.cruip.com/appy/about.html (Andrea e Sebastian)
- Creazione Blog: https://preview.cruip.com/appy/blog.html (Edoardo e Vito)

## FASI:

- Pianificazione, organizzazione e documentazione
- Sviluppo struttura HTML
- Revisione
- Pianificazione, organizzazione e struttura CSS
- Sviluppo struttura CSS
- Revisione 
- Release <-- Siamo qui

## ORGANIZZAZIONE:

Tutti i team si vedranno ogni mattina dalle 9 alle 9.15 per avere una visione generale dell'andamento del progetto, ogni team sarà poi indipendente nella coordinazione con il suo compagno.

L'orario di lavoro sarà dal Lunedì al venerdì 9-11

## WORKFLOW:

- LAVORARE SOLO SU REPO SINCRONIZZATE, Assicurarsi che siano sincronizzate sia da github che da locale.
- FARE COMMIT ATOMICI, in modo da dare flessibilità al progetto, niente blocchi enormi in un singolo commit
- CONTROLLARE LA SEZIONE PROJECT, Le task saranno inserite lì per tutti
- LAVORARE SULLA BRANCH CONDIVISA, MAI SULL' UFFICIALE (Develop) - (Main)

# BRANCH:

Il team lavorerà su branch condivisa:

Develop-about
Develop-homepage
Develop-blog

Nella vostra branch condivisa potete sviluppare queste sotto-branch:

---

Nella vostra branch condivisa potete sviluppare queste sotto-branch:

- Nuova feature: feat/name-of-feature ---> Nuova feature

- Bugfix: fix/bug-fixed-hash ---> Fix di bug

- Refactor: ref/what-i-have-changed ---> Pulizia del codice e miglioramento

- Style: style/new-style ---> cambiamenti minori estetici sul css

## COMMIT

I commit devono spiegare la modifica al codice effettuata, utilizzando questa convenzione:

Nuova feature: commit -m "feat: name of feature"
Bugfix: commit -m "fix: bug fixed - hash"
Style: commit -m "style: style's change"
Refactor: commit -m "ref: refactoring"

# CSS

Il primo obiettivo è la struttura CSS, ordinare i blocchi nello spazio, niente focus sui dettagli e niente overworking.

# Organizzazione

- La struttura deve essere suddivisa in cinque fogli di lavoro:
- - index.css: importa tutti gli altri css;
- - layout.css: componenti grandi della pagina (blocchi es. <section>);
- - components.css: componenti minori della pagina (es <button>, piccoli <div>);
- - typhografy.css: fonts;
- - helpers.css: per le classi helper;

# Convenzioni

# Notazione BEM

Per i nomi delle classi utilizzeremo la notazione BEM

https://www.html.it/pag/50349/bem-block-element-modifier/

- La struttura BEM si compone di tre campi: block\_\_elemnt--modifier;

- - Blocco: nome del contenitore madre (es. card);
- - Element: tipo di elemento (es. title);
- - Modifier: varizione elemento (ed. red);

card\_\_title--red;

card\_\_title--blue;

# Portabilità

Si lavora SOLO con quattro unità di misura:

- rem
- %: si basa sulla dimensione totale del contenitore
- viewport: si bassa sulla dimensione dello schermo
- px (solo per piccole dimensioni, max 5px)

  0.25 rem = 4px / 0.5 rem = 8px / 1 rem = 16px

# Conoscenze necessarie

- display: flex;
- - justify-content;
- - align-content;
- - align-self;
- - gap;
- - flex-direction;

- position: absolute;

## SVILUPPO

Il primo obiettivo è la struttura CSS, ordinare i blocchi nello spazio, niente focus sui dettagli e niente overworking sui dettagli.
