# AMES Technical Test

Aquest repositori conté un projecte FullStack desenvolupat amb Spring Boot per al backend i Vue.js per al frontend. A més, el projecte ha estat dockeritzat per facilitar el desplegament i l'execució en diferents entorns.

## Contingut

- [Descripció](#descripció)
- [Característiques](#característiques)
- [Requisits](#requisits)
- [Instruccions d'instal·lació](#instruccions-dinstal·lació)
- [Execució del projecte](#execució-del-projecte)
- [Contacte](#contacte)

## Descripció

Aquest projecte és un exemple d'una aplicació FullStack que utilitza Spring Boot com a backend i Vue.js com a frontend. L'aplicació presenta un CRUD (Crear, Llegir, Actualitzar i Esborrar) per gestionar certes dades. El backend proporciona una API RESTful que interactua amb una base de dades, mentre que el frontend es fa càrrec de mostrar la interfície d'usuari i permetre la interacció de l'usuari amb l'aplicació.

## Característiques

- Backend desenvolupat amb Spring Boot.
- Frontend desenvolupat amb Vue.js.
- Dockeritzat per facilitar la implementació i distribució.
- API RESTful per realitzar operacions CRUD.
- Base de dades utilitzada: MySQL.

## Requisits

Abans d'instal·lar i executar aquest projecte, assegura't de tenir instal·lat el següent:

- Docker: [https://www.docker.com/get-started](https://www.docker.com/get-started)
- Git: [https://git-scm.com/download/](https://git-scm.com/download/)

## Instruccions d'instal·lació

1. Clona aquest repositori a la teva màquina local:

```bash
git clone https://github.com/peredirtbike/Ames_test
cd Ames_test
```
2. Executa aquesta comanda per aixecar el contenidor docker:
```bash
docker-compose up --build -d
```
3. Assegura't de que els contenidors estiguin "running":
```bash
docker ps
```

## Execució del projecte
  ###frontend
  per accedir al frontend, accedirem a aquesta URL
  [Home](https://localhost:5173)
  [Vista clients](https://localhost:5173/clients)

  ##backend
  [Home](https://localhost:8080)
  [Documentació](https://localhost:8080/docs)

## Contacte
Si tens alguna pregunta o consulta, no dubtis a posar-te en contacte amb nosaltres a peredirtbike@gmail.com.



  



