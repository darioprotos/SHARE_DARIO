
# APPUNTI GIT E GITHUB

#### PRIMA FASE
la prima cosa da fare è scaricare git dal sito ed installatlo
per vedere se è andato a buon fine l installazione aprire il cmd 
e digitare il comando: git --version''

#### SECONDA FASE
bisogna inizializzare la cartella che contiene i nostri file 
con il comando sempre in cmd e posizionadoci nel percorso della cartella da inizializzare per sincronizzarla : git init
a questo punto comparira la cartella GIT che sarà in modalità nascosta 
dentro la cartella che abbiamo deciso di condividere 

#### TERZA FASE
bisogna configurare due variabili globli che sarebbero la user name 
e l'email con 
i seguenti comandi: git config --global user.name "dario"
                    git config --global user.email "darioprotano@gmail.com"
#### QUARTA FASE
creare sul sito di GITHUB una sincronizzazione 
con la cartella che abbiamo creato sul pc locale 
e che su GITHUB si chiama REPOSITORY 
una volta creata la repository copiare il link HTTPS da code per inserirlo sul terminale con il seguente comando :
git remote add origin ed il link che abbiamo copiato da GITHUB in questo modo abbiamo sincronizzato git con github 
per verificare se tutto è andato a buon fine bisogna fare un PULL e cioè fare una richiesta su github per scaricare i file da remoto sulla nosta cartella del progetto git attraverso il comando : git pull origin main




                    