
## Projet API-REST node JS Gestion de membres

Ce projet est une API-REST permettant de voir un ou tous les membres, d'ajouter un membre, 
de le modifier ou encore de le supprimer.

Pour bien commencer

```node
npm install
```
une fois dans le dossier du projet

```node
yarn develop
```

1.Dans Postman, se mettre en POST
2.Route d'authentification : [ngrok ou localhost:1337]/auth/local/register
3.Dans le Body, rentrer (mettre en format JSON): 

```node
{
  "username": "jean",
  "email": "jeanbon@gmail.com",
  "password": "password"
}
```

4.Un Token apparait, le copier

5.Aller sur la route [ngrok ou localhost:1337]/members  -> GET

6.Dans la partie "Authorization", 
sélectionner le type Bearer Token et rentrer le token dans le champs correspondant

7.Access Granted


## Documentation
[API DOCUMENTATION ON SWAGGER LOCAL](http://localhost:1337/documentation/v1.0.0#/)

