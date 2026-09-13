# LiteCopy

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | Français

Une extension légère qui restaure la sélection de texte native, le menu contextuel et les raccourcis de copie sur n'importe quel site web.

> Chromium · Manifest V3 · Permissions minimales · Niveaux gratuit + Premium

---

## Pourquoi LiteCopy ?

Vous avez déjà essayé de copier du texte depuis un site web mais impossible de le sélectionner, le clic droit était bloqué, ou Ctrl+C ne faisait rien ? LiteCopy corrige tout ça en un clic.

| Avantage | Détail |
|-----------|--------|
| 🔓 **Activation en un clic** | Restaure la sélection de texte native instantanément — aucun rechargement de page nécessaire |
| 🔒 **Permissions minimales** | `activeTab` + `scripting` + `storage` — rien de plus que ce dont la fonctionnalité a besoin |
| ⚡ **Léger** | Pas de frameworks, pas de dépendances d'exécution |
| 🌍 **6 langues** | English, 中文, Español, Deutsch, 日本語, Français |
| 🚫 **Pas de suivi** | Pas d'analytics, pas de télémétrie. Le niveau gratuit n'envoie aucune donnée ; l'activation Premium vérifie uniquement un identifiant d'appareil + votre clé sur api.annmax1983.com |
| 🎯 **Interrupteur simple** | Ouvrez le popup et appuyez sur Activer/Désactiver — indicateur d'état ON/OFF clair |

---

## Fonctionnalités

### 🆓 Gratuit (100 copies/jour)

| Fonctionnalité | Description |
|---------|-------------|
| 🔓 **Restaurer la sélection de texte** | Restaure la sélection de texte par défaut sur les sites qui la désactivent |
| 🖱️ **Restaurer le menu contextuel** | Restaure le menu contextuel du navigateur sur les sites restreints |
| ⌨️ **Restaurer les raccourcis clavier** | Restaure Ctrl+C, Ctrl+V, Ctrl+A et les autres raccourcis standards |
| 🛡️ **Corriger les overlays** | Corrige les divs transparentes qui interfèrent avec la sélection de texte |
| 🔄 **Interrupteur ON/OFF** | Activez/Désactivez depuis le popup, la page se recharge à la désactivation |
| 💬 **Notification toast** | Notification auto-fermante affichant le statut d'activation |
| 📋 **Copier les infos de la page** | Boutons du popup pour copier le titre de la page, l'URL, ou les deux |

> **Limite du niveau gratuit :** 100 copies par jour. L'activation est toujours gratuite — chaque copie effectuée sur une page activée compte dans la limite quotidienne. Le compteur se réinitialise à minuit (heure locale). Les boutons Copier les infos (titre/URL) sont toujours gratuits et ne comptent pas.

### ⭐ Premium (licence requise — illimité)

| Fonctionnalité | Description |
|---------|-------------|
| ♾️ **Copies illimitées** | Pas de limite quotidienne — copiez autant que vous voulez |
| 📤 **Export/Import des paramètres** | Sauvegardez et restaurez vos préférences (bientôt disponible) |

> 💡 Achat unique ou abonnement mensuel. [Obtenir une licence →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Tarifs

| Plan | Prix | Détails |
|------|-------|---------|
| Gratuit | 0 $ | 100 copies/jour, toutes les fonctionnalités de base |
| Outil individuel mensuel | 2,99 $/mois | Copies illimitées pour LiteCopy |
| Outil individuel à vie | 9,99 $ | Paiement unique, accès permanent |
| Suite complète mensuelle | 3,99 $/mois | Toutes les extensions VKT, illimité |
| Suite complète à vie | 19,99 $ | Toutes les extensions VKT, permanent |

Voir les [tarifs VKT](https://www.annmax1983.com/pricing.html) pour plus de détails.

---

## Aperçu

<p align="center">
  <img src="icons/icon128.png" alt="Icône LiteCopy" width="80">
</p>

---

## Navigateurs compatibles

| Navigateur | Statut |
|---------|--------|
| Google Chrome | ✅ Entièrement pris en charge |
| Microsoft Edge | ✅ Entièrement pris en charge |
| Autres navigateurs basés sur Chromium | ✅ Devrait fonctionner |

---

## Installation

1. Ouvrez la page des extensions de votre navigateur :
   - **Chrome** : `chrome://extensions/`
   - **Edge** : `edge://extensions/`
2. Activez le **mode Développeur** (bouton en haut à droite)
3. Cliquez sur **Charger le package décompressé** et sélectionnez le dossier `lite-copy`
4. L'icône LiteCopy apparaît dans votre barre d'outils

---

## Utilisation

1. Visitez un site qui bloque la copie ou la sélection de texte
2. Cliquez sur l'icône **LiteCopy** dans votre barre d'outils — le popup s'ouvre
3. Cliquez sur **Activer** — la sélection de texte est restaurée instantanément
4. Pour désactiver, rouvrez le popup et cliquez sur **Désactiver** (la page se recharge pour restaurer le comportement original)

> **Note :** Certaines pages restreintes par le navigateur (`chrome://`, le Chrome Web Store, etc.) ne peuvent pas être modifiées. Le popup affiche une erreur.

**Copier les infos de la page :**
- Cliquez sur l'icône → le popup s'ouvre
- Utilisez les boutons pour copier le titre de la page, l'URL, ou les deux

**Vérifier l'utilisation :**
- La barre d'utilisation en haut affiche votre nombre de copies du jour
- Utilisateurs gratuits : 100 copies/jour, réinitialisation à minuit
- Utilisateurs Premium : ⭐ Illimité

---

## Confidentialité

- ✅ **Pas d'analytics** — Aucun suivi, aucune télémétrie
- ✅ **Niveau gratuit : zéro requête réseau** — Tout le traitement se fait en local ; rien n'est envoyé tant que vous n'activez pas le Premium
- ✅ **Permissions minimales** — `activeTab` + `scripting` + `storage`, plus l'hôte de l'API de licence
- ✅ **Pas de mémoire de sites** — Pas de liste noire/blanche, pas de préférences par site stockées
- ✅ **Vérification de licence uniquement** — Si vous activez une licence Premium, un identifiant d'appareil minimal et votre clé de licence sont envoyés à `api.annmax1983.com` pour vérification. Aucune donnée n'est envoyée si vous n'activez pas de licence.

---

## Avertissement relatif au droit d'auteur

Cet outil restaure uniquement les fonctions natives de manipulation de texte du navigateur pour l'apprentissage personnel, la consultation et la lecture hors ligne des utilisateurs. Tous les droits d'auteur des textes, images et contenus des sites appartiennent à leurs auteurs et opérateurs originaux. Les utilisateurs ne doivent pas utiliser cet outil à des fins de reproduction commerciale, d'extraction massive, de republication de contenus ou de toute autre activité portant atteinte au droit d'auteur. Toute responsabilité juridique découlant d'une utilisation inappropriée incombe exclusivement à l'utilisateur.

---

## Avis sur le code source

> ⚠️ **Ce dépôt ne publie pas le code source.** Il contient uniquement la documentation d'utilisation, les notes de version et les ressources d'assistance. L'extension est distribuée exclusivement via le Chrome Web Store. Aucun package d'installation hors ligne ni code source destiné aux utilisateurs finaux n'est fourni.

---

## Licence

Copyright © 2026 LiteCopy. Tous droits réservés.

---

## ❤️ Soutenir

Si LiteCopy vous est utile, n'hésitez pas à soutenir le projet !

**[👉 Cliquez ici pour soutenir](https://ko-fi.com/annmax?ref=litecopy)**
