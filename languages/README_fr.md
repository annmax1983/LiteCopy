# LiteCopy

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | Français

Une extension légère qui restaure la sélection de texte native, le menu contextuel et les raccourcis de copie sur n'importe quel site web.

> Chrome / Edge / Firefox · Manifest V3 · Copies gratuites illimitées · Règles de sites entre appareils en Premium

---

## Pourquoi LiteCopy ?

Vous avez déjà essayé de copier du texte depuis un site web mais impossible de le sélectionner, le clic droit était bloqué, ou Ctrl+C ne faisait rien ? LiteCopy corrige tout ça en un clic.

| Avantage | Détail |
|-----------|--------|
| 🔓 **Activation en un clic** | Restaure la sélection de texte native instantanément — aucun rechargement de page nécessaire |
| ♾️ **Gratuit et illimité** | Copiez, sélectionnez et utilisez le clic droit autant que vous voulez — sans limite quotidienne ni compteur |
| 🔄 **Règles de sites entre appareils** | Premium synchronise les sites que vous activez via le compte intégré du navigateur (Chrome Sync / Edge Sync) |
| 🔒 **Local par conception** | Le déblocage s'exécute localement avec `activeTab` + `scripting` ; l'accès aux sites ne sert qu'aux pages que vous activez |
| ⚡ **Léger** | Pas de frameworks, pas de dépendances d'exécution |
| 🌍 **6 langues** | English, 中文, Español, Deutsch, 日本語, Français |
| 🚫 **Pas de suivi** | Pas d'analytics, pas de télémétrie. Le développeur n'a aucun serveur stockant votre historique ou votre liste de sites |
| 🎯 **Interrupteur simple** | Ouvrez le popup et appuyez sur Activer/Désactiver — indicateur d'état ON/OFF clair |

---

## Fonctionnalités

### 🆓 Gratuit — illimité

| Fonctionnalité | Description |
|---------|-------------|
| 🔓 **Restaurer la sélection de texte** | Restaure la sélection de texte par défaut sur les sites qui la désactivent |
| 🖱️ **Restaurer le menu contextuel** | Restaure le menu contextuel du navigateur sur les sites restreints |
| ⌨️ **Restaurer les raccourcis clavier** | Restaure Ctrl+C, Ctrl+V, Ctrl+A et les autres raccourcis standards |
| 🛡️ **Corriger les overlays** | Corrige les divs transparentes qui interfèrent avec la sélection de texte |
| 🔄 **Interrupteur ON/OFF** | Activez/Désactivez depuis le popup, la page se recharge à la désactivation |
| 🧠 **Sites mémorisés** | Les sites que vous activez sont mémorisés localement et réactivés automatiquement à la prochaine visite |
| 💬 **Notification toast** | Notification auto-fermante affichant le statut d'activation |
| 📋 **Copier les infos de la page** | Boutons du popup pour copier le titre de la page, l'URL, ou les deux |

> Toutes les fonctions ci-dessus sont gratuites et illimitées — aucun quota quotidien, aucun compteur.

### ⭐ Premium — règles de sites entre appareils

| Fonctionnalité | Description |
|---------|-------------|
| 🔄 **Règles de sites entre appareils** | Activez un site une fois et la règle suit votre compte navigateur : elle sera réactivée automatiquement sur vos autres appareils connectés au même compte |
| 🔐 **Synchronisation via le compte navigateur** | La liste est stockée par votre navigateur dans `storage.sync`. Aucun compte LiteCopy, aucune copie sur un serveur développeur, et le développeur n'y a pas accès |
| 💻 **Accès par appareil** | Les autorisations de site du navigateur ne peuvent pas être synchronisées. Sur un nouvel appareil, cliquez une fois sur **Activer** pour le site synchronisé afin d'accorder l'accès — la règle est déjà enregistrée |
| 🧭 **Synchronisation manuelle** | Le bouton **Synchroniser** des paramètres récupère la liste la plus récente depuis votre compte navigateur à tout moment |

> 💡 Achat unique ou abonnement mensuel. [Obtenir une licence →](https://www.annmax1983.com/checkout.html?plugin=litecopy)

---

## Aperçu

<p align="center">
  <img src="../assets/favicon.png" alt="Icône LiteCopy" width="80">
</p>

---

## Navigateurs compatibles

| Navigateur | Statut |
|---------|--------|
| Google Chrome | ✅ Entièrement pris en charge |
| Microsoft Edge | ✅ Entièrement pris en charge |
| Mozilla Firefox | ✅ Entièrement pris en charge |
| Autres navigateurs basés sur Chromium | ✅ Devrait fonctionner |

> **Note Firefox :** Les pages protégées sont les pages `about:` et addons.mozilla.org. La synchronisation entre appareils passe par Firefox Sync (compte Mozilla). Le reste des fonctions se comporte comme sous Chrome / Edge.

---

## Installation

| Store | Lien |
|---|---|
| Chrome Web Store | [Installer dans Chrome](https://chromewebstore.google.com/detail/opckcochfnlfcdoblnmgeebeeggfnilg) |
| Microsoft Edge Add-ons | [Installer dans Edge](https://microsoftedge.microsoft.com/addons/detail/acpfcfipfalphidhmpflecncacgldggl) |
| Modules complémentaires Firefox (AMO) | 🔜 En cours d’examen — le lien sera ajouté après publication |

> Installez uniquement depuis les boutiques officielles ci-dessus — évitez les sites de téléchargement tiers.

---

## Utilisation

1. Visitez un site qui bloque la copie ou la sélection de texte
2. Cliquez sur l'icône **LiteCopy** dans votre barre d'outils — le popup s'ouvre
3. Cliquez sur **Activer** — la sélection de texte est restaurée instantanément
4. Pour désactiver, rouvrez le popup et cliquez sur **Désactiver** (la page se recharge pour restaurer le comportement original)

> **Note :** Certaines pages restreintes par le navigateur (`chrome://`, le Chrome Web Store, Microsoft Edge Add-ons et Firefox Add-ons (AMO), etc.) ne peuvent pas être modifiées. Le popup affiche une erreur.

**Règles de sites et synchronisation (Premium) :**
- Activez un site sur un appareil — la règle est ajoutée au stockage synchronisé de votre compte navigateur
- Sur un autre appareil connecté au même compte navigateur, le site apparaît comme règle enregistrée ; cliquez une fois sur **Activer** pour accorder l'autorisation de site de cet appareil
- Ouvrez les **Paramètres** pour voir le nombre de sites synchronisés et utilisez **Synchroniser** pour actualiser immédiatement

**Copier les infos de la page :**
- Cliquez sur l'icône → le popup s'ouvre
- Utilisez les boutons pour copier le titre de la page, l'URL, ou les deux

---

## Confidentialité

- ✅ **Pas d'analytics** — Aucun suivi, aucune télémétrie
- ✅ **Fonctions gratuites : zéro requête réseau** — Tout le traitement se fait en local ; rien n'est envoyé tant que vous n'activez pas le Premium
- ✅ **Permissions ciblées** — `activeTab` + `scripting` + `storage` exécutent le déblocage, plus l'accès aux sites utilisé uniquement pour l'injecter sur les pages que vous activez, et l'hôte de l'API de licence
- ✅ **Liste de sites locale par défaut** — Activer LiteCopy enregistre ce domaine dans `storage.local`. Cette liste n'est jamais envoyée au développeur
- ✅ **La synchronisation Premium utilise votre compte navigateur** — Avec une licence active, la liste est aussi reflétée dans `storage.sync`, la synchronisation de compte de votre fournisseur de navigateur. Le développeur n'y a pas accès et n'en reçoit aucune copie. La synchronisation s'arrête si vous supprimez la licence ; les règles locales continuent de fonctionner
- ✅ **Vérification de licence uniquement** — Si vous activez une licence Premium, un identifiant d'installation minimal et votre clé de licence sont envoyés à `api.annmax1983.com` pour vérification. Aucune donnée n'est envoyée si vous n'activez pas de licence

---

## Avertissement relatif au droit d'auteur

Cet outil restaure uniquement les fonctions natives de manipulation de texte du navigateur pour l'apprentissage personnel, la consultation et la lecture hors ligne des utilisateurs. Tous les droits d'auteur des textes, images et contenus des sites appartiennent à leurs auteurs et opérateurs originaux. Les utilisateurs ne doivent pas utiliser cet outil à des fins de reproduction commerciale, d'extraction massive, de republication de contenus ou de toute autre activité portant atteinte au droit d'auteur. Toute responsabilité juridique découlant d'une utilisation inappropriée incombe exclusivement à l'utilisateur.

---

## Avis sur le code source

> ⚠️ **Ce dépôt ne publie pas le code source.** Il contient uniquement la documentation d'utilisation et les ressources d'assistance. L'extension est distribuée exclusivement via le Chrome Web Store, Microsoft Edge Add-ons et Firefox Add-ons (AMO). Aucun package d'installation hors ligne ni code source destiné aux utilisateurs finaux n'est fourni.

---

## Politique de Confidentialité

Consultez la [Politique de Confidentialité](../privacy-policy.html) complète — les fonctions gratuites fonctionnent entièrement hors ligne, sans aucune requête réseau.

---

## Licence

Copyright © 2026 LiteCopy. Tous droits réservés.

---

## ❤️ Soutenir

Si LiteCopy vous est utile, n'hésitez pas à soutenir le projet !

**[👉 Cliquez ici pour soutenir](https://ko-fi.com/annmax?ref=litecopy)**
