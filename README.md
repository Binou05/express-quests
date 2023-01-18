# express-quests
Quete 03

## userHandlers.js

ajout de postUser, dans le module.exports

## app.js

ajout de la route

```
app.post("/api/users", userHandlers.postUser);
```

## Critères d'acceptation

- [x] Le GitHub contient une route POST pour les utilisateurs
- [x] Une requête POST sur /api/users devrait créer un nouvel utilisateur dans la base de données
