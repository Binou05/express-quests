# express-quests
Quete 04

## userHandlers.js

ajout de updateUser, dans le module.exports

## app.js

ajout de la route

```
app.put("/api/users", userHandlers.updateUser);
```

## Critères d'acceptation

- [x] Le GitHub contient une route PUT pour les utilisateurs
- [x] Une requête PUT sur /api/users devrait créer un nouvel utilisateur dans la base de données
