# Protocole SSH

## 1. Présentation

SSH signifie **Secure Shell**.

Il permet de se connecter à un serveur distant de manière sécurisée.

## 2. Fonctionnement

1. Le client contacte le serveur.
2. Le serveur et le client établissent une connexion sécurisée.
3. Le client s'authentifie.
4. Le serveur autorise ou refuse l'accès.

## 3. Méthodes d'authentification

| Méthode | Avantage | Inconvénient |
|---|---|---|
| Mot de passe | Simple à utiliser | Sensible aux mots de passe faibles |
| Clé publique | Bonne sécurité | Gestion des clés nécessaire |

## 4. Conclusion

L'authentification par clé publique est généralement recommandée,
avec une clé privée protégée et des algorithmes adaptés aux menaces quantiques.
