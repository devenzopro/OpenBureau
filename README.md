# 🏢 OpenBureau

**Un réseau d’entreprise complet et gratuit, basé sur Zorin OS et des logiciels open source.**

OpenBureau rassemble des scripts et des guides pour monter, pas à pas, l’infrastructure d’une petite ou moyenne entreprise : postes de travail, annuaire, serveur de fichiers, mises à jour centralisées, antivirus, proxy, chiffrement… uniquement avec des logiciels libres.

Le projet est **modulaire** : chaque service est indépendant. Tu peux installer seulement ce dont tu as besoin, dans l’ordre que tu veux.

> 👤 Projet créé et maintenu par **Dev-Enzo**
> 🌱 Projet personnel qui évolue au fil du temps, sans planning fixe.

---

## 🎯 Objectifs

- Proposer une alternative libre aux solutions d’entreprise propriétaires
- Tout centraliser au même endroit : scripts, configurations et documentation
- Rester simple à comprendre, à installer et à adapter
- Être accessible gratuitement à tout le monde

---

## 🧩 Modules

| Module | Rôle | Logiciel prévu | État |
|---|---|---|---|
| `postes` | Configuration des PC sous Zorin OS | Scripts Bash | 💡 Idée |
| `annuaire` | Comptes et authentification centralisés (AD) | Samba AD | 💡 Idée |
| `fichiers` | Partage de fichiers réseau | Samba | 💡 Idée |
| `mises-a-jour` | Cache local des paquets et mises à jour | apt-cacher-ng | 💡 Idée |
| `antivirus` | Protection antivirus des postes et serveurs | ClamAV | 💡 Idée |
| `proxy` | Filtrage et cache web | Squid | 💡 Idée |
| `chiffrement` | Chiffrement des disques et données | LUKS | 💡 Idée |

**Légende :** ✅ Fonctionnel · 🚧 En cours · 💡 Idée

---

## 📁 Structure du dépôt

```
OpenBureau/
├── README.md          ← ce fichier
├── LICENSE
├── postes/            ← scripts pour les PC Zorin OS
├── modules/
│   ├── annuaire/
│   ├── fichiers/
│   ├── mises-a-jour/
│   ├── antivirus/
│   ├── proxy/
│   └── chiffrement/
└── docs/
```

Chaque module contient son propre `README.md` qui explique ce qu’il fait et comment l’installer.

---

## 🚀 Utilisation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/devenzopro/OpenBureau.git
   cd OpenBureau
   ```
2. Choisir le module voulu dans `modules/` ou `postes/`.
3. Suivre le `README.md` du module ou le guide correspondant dans le [Wiki](https://github.com/devenzopro/OpenBureau/wiki).

> ⚠️ Teste toujours les scripts sur une machine de test ou une machine virtuelle avant de les utiliser en production.

---

## 📖 Documentation

Les tutoriels détaillés et les explications se trouvent dans le **[Wiki du projet](https://github.com/devenzopro/OpenBureau/wiki)**.

---

## 🤝 Contribuer

Les idées, remarques et corrections sont les bienvenues !

- 💡 Une idée de module ou d’amélioration ? Ouvre une [issue](https://github.com/devenzopro/OpenBureau/issues).
- 🐛 Un bug dans un script ? Ouvre une issue en décrivant le problème.
- 🔧 Une correction ? Propose une pull request sur ce dépôt.

---

## 📜 Licence

Ce projet est distribué sous la **Licence OpenBureau**. Voir le fichier [LICENSE](LICENSE).

En résumé :
- ✅ Utilisation gratuite, personnelle ou en entreprise (y compris en production)
- ✅ Adaptation des paramètres à ton réseau (IP, domaine, chemins…)
- ✅ Partage de la version originale, gratuitement
- ❌ Modification et redistribution d’une version modifiée
- ❌ Revente ou intégration dans une offre payante
- ❌ Suppression de la mention « OpenBureau — Dev-Enzo »

Les logiciels installés par OpenBureau (Zorin OS, Samba, ClamAV, Squid…) restent sous leurs propres licences.

---

## ℹ️ Mention

OpenBureau est un projet indépendant. Il n’est ni affilié à, ni soutenu par Zorin Group. *Zorin OS* est une marque de Zorin Group.
