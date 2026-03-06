# Pràctica 1 - Aplicació Flask

## Descripció
Aquesta aplicació és una web desenvolupada amb **Flask** que permet introduir els noms dels integrants d’un grup mitjançant un formulari HTML.
Els noms introduïts es processen al servidor i es mostren dinàmicament a la pàgina. 
A més, es guarden en una base de dades **SQLite**, de manera que es mantenen entre execucions de l’aplicació.

D'altra banda, l’aplicació també inclou contingut estàtic com imatges dins del directori `static/`.

---

## Instruccions per executar l’aplicació en local

### 0. Clonar el repositori.
```bash
git clone https://github.com/EL_TEU_USUARI/practica1-flask.git
cd practica1-flask
```
### 1. Crear i activar l'entorn virtual
```bash
python3 -m venv venv
source venv/bin/activate
```
### 2. Instal·lació de les dependencies.
```bash
pip install -r requirements.txt
```
### 3. Executar l'aplicació
```bash
python app.py
```
### 4. Accés a l'aplicació.
Per accedir a l'aplicació, obre el navegador i accedeix a aquest link:
http://127.0.0.1:8000




