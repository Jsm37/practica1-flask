# Pràctica 1 - Aplicació Flask

## Descripció
Aquesta aplicació és una web desenvolupada amb **Flask** que permet introduir els noms dels integrants d’un grup mitjançant un formulari HTML.
Els noms introduïts es processen al servidor i es mostren dinàmicament a la pàgina. A més, es guarden en una base de dades **SQLite**, de manera que es mantenen entre execucions de l’aplicació.
D'altra banda, l’aplicació també inclou contingut estàtic com imatges dins del directori `static/`.

---

## Instruccions per executar l’aplicació en local
```bash
// Clonar el repositori.
git clone https://github.com/EL_TEU_USUARI/practica1-flask.git
cd practica1-flask

// Crear l'entorn virtual
python3 -m venv venv

// Activar l'entorn virtual
source venv/bin/activate

// Instal·lació de les dependencies necessaries pel
pip install -r requirements.txt
