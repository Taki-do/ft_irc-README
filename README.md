# 💬 ft_irc

**ft_irc** est une implémentation simplifiée d’un serveur IRC (Internet Relay Chat).  
Le but est de comprendre le fonctionnement d’un protocole réseau et de gérer plusieurs clients connectés simultanément.

---

## 🎯 Objectif

- Implémenter un serveur IRC conforme à la RFC 2812.  
- Gérer plusieurs connexions TCP.  
- Gérer les salons, les commandes et les messages.

---

## ⚙️ Lancement

```bash
make
./ircserv <port> <password>
```
## 🧩 Fonctionnalités

- Connexion multi-clients via sockets
- Authentification par mot de passe
- Commandes IRC principales :
**/nick, /join, /part, /privmsg, /kick, /topic, /mode**
- Gestion des salons et permissions
- Communication avec poll()

## 👔 Recruteurs
Si vous êtes un recruteur et que vous voulez obtenir le code source, vous pouvez me contacter ici : **taomalbe@student.42perpignan.fr**

## Auteurs
- [vorace32](https://github.com/vorace3200)
- [qbarron](https://github.com/Sul-iac)
- [taomalbe](https://github.com/Taki-do)
