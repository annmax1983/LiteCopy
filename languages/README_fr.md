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
| 🔄 **Règles de sites entre appareils** | Premium synchronise les sites que vous activez via le compte intégré du navigateur (Chrome Sync / Edge Sync / Firefox Sync) |
| 🔒 **Local par conception** | Le déblocage s'exécute localement avec `activeTab` + `scripting` ; l'accès aux sites ne sert qu'aux pages que vous activez |
| ⚡ **Léger** | Pas de frameworks, pas de dépendances d'exécution |
| 🌍 **6 langues** | Anglais, chinois, espagnol, allemand, japonais, français |
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
| 🖱️ **Actions du menu contextuel** | Activez un site, désactivez la page actuelle, copiez le titre et l'URL de la page ou ouvrez le gestionnaire de sites directement depuis le menu contextuel de la page |
| 🗂 **Gestionnaire de sites** | Une page indépendante qui liste chaque domaine mémorisé, l'accès dont dispose cet appareil et son mode Complet/Léger — chaque ligne se retire après une confirmation |
| 🪶 **Mode Léger par site** | Pour les sites avec captchas à glissière ou éditeurs de texte enrichi, restaure uniquement le clic droit et la sélection — LiteCopy laisse totalement intacts les événements de copie et de clavier |

> Toutes les fonctions ci-dessus sont gratuites et illimitées — aucun quota quotidien, aucun compteur.

### ⭐ Premium — règles de sites entre appareils

| Fonctionnalité | Description |
|---------|-------------|
| 🔄 **Règles de sites entre appareils** | Activez un site une fois et la règle suit votre compte navigateur : elle sera réactivée automatiquement sur vos autres appareils connectés au même compte |
| 🔐 **Synchronisation via le compte navigateur** | La liste est stockée par votre navigateur dans `storage.sync`. Aucun compte LiteCopy, aucune copie sur un serveur développeur, et le développeur n'y a pas accès |
| 💻 **Accès par appareil** | Les autorisations de site du navigateur ne peuvent pas être synchronisées. Sur un nouvel appareil, cliquez une fois sur **Activer** pour le site synchronisé afin d'accorder l'accès — la règle est déjà enregistrée |
| 🧭 **Synchronisation manuelle** | Le bouton **Synchroniser** des paramètres récupère la liste la plus récente depuis votre compte navigateur à tout moment |
| 📦 **Sauvegarde et transfert des règles** | Exportez tous les sites mémorisés (avec leur mode Complet/Léger) dans un fichier JSON et importez-les sur un autre profil de navigateur ou un autre appareil |

> 💡 Achat unique. [Obtenir une licence →](https://annmax1983.com/checkout?plugin=litecopy)

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
| Modules complémentaires Firefox (AMO) | [Installer pour Firefox](https://addons.mozilla.org/firefox/addon/litecopy-enable-copy/) |

> Installez uniquement depuis les boutiques officielles ci-dessus — évitez les sites de téléchargement tiers.

---

## Utilisation

1. Visitez un site qui bloque la copie ou la sélection de texte
2. Cliquez sur l'icône **LiteCopy** dans votre barre d'outils — le popup s'ouvre
3. Cliquez sur **Activer** — la sélection de texte est restaurée instantanément
4. Pour désactiver, rouvrez le popup et cliquez sur **Désactiver** (la page se recharge pour restaurer le comportement original)

> **Note :** Certaines pages restreintes par le navigateur (`chrome://`, le Chrome Web Store, Microsoft Edge Add-ons et Firefox Add-ons (AMO), etc.) ne peuvent pas être modifiées. Le popup affiche une erreur.

**Menu contextuel :**
- Faites un clic droit sur n'importe quelle page pour **Activer sur ce site**, **Désactiver sur cette page**, **Copier le titre et l'URL de la page** ou ouvrir **Gérer les sites**
- L'activation depuis le menu demande l'accès au site une seule fois ; si vous refusez, l'onglet actuel est quand même débloqué pour cette visite

**Gestionnaire de sites :**
- Ouvrez-le depuis le bouton **Gérer les sites** du popup ou depuis le menu contextuel
- Chaque domaine mémorisé est listé avec l'accès de cet appareil, un interrupteur **Complet / Léger** et un bouton **Retirer** qui demande un second clic pour confirmer
- Le mode **Léger** restaure uniquement le clic droit et la sélection de texte. Les gestionnaires de copie et de clavier ne sont pas touchés, ce qui laisse les captchas à glissière et les éditeurs de texte enrichi fonctionner normalement

**Règles de sites et synchronisation (Premium) :**
- Activez un site sur un appareil — la règle est ajoutée au stockage synchronisé de votre compte navigateur
- Sur un autre appareil connecté au même compte navigateur, le site apparaît comme règle enregistrée ; cliquez une fois sur **Activer** pour accorder l'autorisation de site de cet appareil
- Ouvrez les **Paramètres** pour voir le nombre de sites synchronisés et utilisez **Synchroniser** pour actualiser immédiatement
- **Exporter / Importer** se trouvent dans la carte **Sauvegarde et transfert** du gestionnaire de sites, pas dans le popup : ils sauvegardent la liste des sites (mode Léger inclus) dans un fichier JSON et la restaurent sur un autre profil. Les choix Complet et Léger restent enregistrés sur chaque appareil ; seule la liste des domaines se synchronise automatiquement

**Copier les infos de la page :**
- Cliquez sur l'icône → le popup s'ouvre
- Utilisez les boutons pour copier le titre de la page, l'URL, ou les deux

---

## Confidentialité

- ✅ **Pas d'analytics** — Aucun suivi, aucune télémétrie
- ✅ **Fonctions gratuites : zéro requête réseau** — Tout le traitement se fait en local ; rien n'est envoyé tant que vous n'activez pas le Premium
- ✅ **Permissions ciblées** — `activeTab` + `scripting` + `storage` exécutent le déblocage, `contextMenus` sert uniquement à ajouter des entrées LiteCopy au menu contextuel du navigateur, `alarms` uniquement à la revérification périodique de la licence Premium, plus l'accès aux sites utilisé uniquement pour l'injecter sur les pages que vous activez, et l'hôte de l'API de licence
- ✅ **Liste de sites locale par défaut** — Activer LiteCopy enregistre ce domaine dans `storage.local`. Cette liste n'est jamais envoyée au développeur
- ✅ **La synchronisation Premium utilise votre compte navigateur** — Avec une licence active, la liste est aussi reflétée dans `storage.sync`, la synchronisation de compte de votre fournisseur de navigateur. Le développeur n'y a pas accès et n'en reçoit aucune copie. La synchronisation s'arrête si vous supprimez la licence ; les règles locales continuent de fonctionner
- ✅ **Vérification de licence uniquement** — Si vous activez une licence Premium, votre clé de licence, un identifiant d'installation aléatoire, l'identifiant de l'extension et des métadonnées de navigateur (navigateur, liste de langues, fuseau horaire, user agent) sont envoyés à `api.annmax1983.com` pour vérification — les mêmes champs que ceux décrits dans la politique de confidentialité. Aucune donnée n'est envoyée si vous n'activez pas de licence

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

---

## Liens

- **Site officiel:** https://annmax1983.com/
- **Cette extension:** https://annmax1983.com/extensions/litecopy
- **Confidentialité:** https://annmax1983.com/privacy
- **Contact:** support@annmax1983.com
