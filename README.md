# Yabetoo Documentation

Documentation officielle de Yabetoo - La solution de paiement Mobile Money la plus simple pour l'Afrique.

## À propos de Yabetoo

Yabetoo fournit une infrastructure de paiement complète pour les entreprises en Afrique. Acceptez les paiements Mobile Money de MTN, Airtel et d'autres opérateurs dans plusieurs pays.

### Fonctionnalités principales

- **Paiements** - Acceptez les paiements Mobile Money via page de checkout hébergée ou API
- **Décaissements** - Envoyez de l'argent à vos clients, partenaires ou employés
- **Transferts internationaux** - Gérez les remises transfrontalières
- **Liens de paiement** - Créez des liens de paiement partageables sans code
- **Webhooks** - Recevez des notifications en temps réel sur les transactions

### Opérateurs supportés

| Méthode | Opérateurs | Pays |
|---------|------------|------|
| Mobile Money | MTN, Airtel | Congo (CG) |

## Structure du projet

```
docs/
├── en/                    # Documentation en anglais
│   ├── api-reference/     # Référence API complète
│   ├── developer-tools/   # SDKs, webhooks, tests
│   ├── guides/            # Guides et concepts clés
│   ├── payments/          # Paiements, décaissements, transferts
│   └── platforms/         # Études de cas par secteur
├── fr/                    # Documentation en français
│   └── ...                # Même structure que /en
└── docs.json              # Configuration Mintlify
```

## SDKs disponibles

| Langage | Package | Installation |
|---------|---------|--------------|
| JavaScript/TypeScript | [@yabetoo/sdk-js](https://www.npmjs.com/package/@yabetoo/sdk-js) | `npm install @yabetoo/sdk-js` |
| Python | [yabetoo-sdk](https://pypi.org/project/yabetoo-sdk/) | `pip install yabetoo-sdk` |
| PHP | yabetoo/yabetoo-php | `composer require yabetoo/yabetoo-php` |
| Java | com.yabetoo:yabetoo-java | Maven/Gradle |

## Développement local

Installer le [Mintlify CLI](https://www.npmjs.com/package/mintlify) pour prévisualiser la documentation localement :

```bash
npm i -g mintlify
```

Lancer le serveur de développement à la racine du projet (où se trouve `docs.json`) :

```bash
mintlify dev
```

La documentation sera disponible sur `http://localhost:3000`.

## Publication

Les changements sont automatiquement déployés en production après un push sur la branche principale via l'application GitHub Mintlify.

## Dépannage

- **Mintlify dev ne démarre pas** - Exécuter `mintlify install` pour réinstaller les dépendances
- **Page 404** - Vérifier que vous êtes dans un dossier contenant `docs.json`

## Liens utiles

- [Documentation en ligne](https://docs.yabetoopay.com)
- [Dashboard Yabetoo](https://app.yabetoo.com)
- [API Sandbox](https://pay.sandbox.yabetoopay.com)
- [Site web](https://yabetoopay.com)
- [Support](mailto:support@yabetoopay.com)

## Réseaux sociaux

- [LinkedIn](https://www.linkedin.com/company/yabetoopay/)
- [Facebook](https://www.facebook.com/Yabetoopay/)
