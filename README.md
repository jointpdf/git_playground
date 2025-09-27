# Git Playground
In questo progetto imparo ad usare git e github.  
Come primo esercizio inizializzo una cartella git in locale e la associo a github.

##### Step 1: Inizializzo una cartella git in locale 
```bash
#Inizializzo una nuova cartella Git vuota nella cartella corrente:
$ git init
#Modifico il nome del ramo principale da master in main:
$git branch -m master main
#Se non presenti creo il file README.md e .gitignore:
$echo "Il file README.md è un markdown file dove per convenzione si riassume il senso del progetto" >> README.md
$echo "#ogni riga del file .gitignore indica una tipologia di file o un file specifico che git deve ignorare" >> .gitignore
#Aggiungo i file presenti nella cartella corrente alla staging area di git, in attesa del commit:
$ git add .
#Registro le modifiche effettuate:
$ git commit -m "primo commit"
```

##### Step 2: Associo il progetto ad una cartella github remota
```bash
#Associo una cartella in github alla cartella locale:
$git remote add origin https//...
#Invio i commit locali del branch main al remoto e lo importo come upstream:
$git push -u origin main
```

Come secondo esercizio scarico in locale un progetto da github.

##### Step 1: Clono il progetto remoto in una cartella git locale
```bash
#clono il progetto da github
$git clone https//...
#
$
```
