# Graveson Provence Basket Club 🏀

Site web officiel du **Graveson Provence Basket Club (GPBC)** — club de basketball 100% féminin à Graveson, Provence.

🌐 **Site public** : `https://christophecros-debug.github.io/gpbc-graveson.github.io`
🔐 **Administration** : `https://christophecros-debug.github.io/gpbc-graveson.github.io/admin.html`

## Structure du projet

```
gpbc-graveson.github.io/
├── index.html     ← site public
├── admin.html     ← interface d'administration (protégée par mot de passe)
├── images/
│   ├── logo.png
│   ├── pressoirs.jpg
│   ├── tpk.jpg
│   └── uexpress.png
└── README.md
```

## Page d'administration

Accéder à `admin.html` — mot de passe par défaut : **GPBC2026**
*(à changer dès la première connexion depuis l'onglet Sécurité)*

Depuis l'admin vous pouvez :
- **Événements** : ajouter, modifier, supprimer des événements (matchs, tournois, AG...)
- **Horaires** : gérer les créneaux d'entraînement par jour et catégorie
- **Sponsors** : gérer la liste des sponsors et leurs logos
- **Sécurité** : changer le mot de passe d'accès

> ⚠️ Les données sont stockées dans le `localStorage` du navigateur.
> Chaque membre du bureau doit configurer son mot de passe sur son propre appareil.

## Ajouter une photo d'équipe

Remplacer le bloc `intro-placeholder` dans `index.html` par :
```html
<img src="images/photo-equipe.jpg" alt="L'équipe GPBC" style="width:100%;height:100%;object-fit:cover;">
```

## Déployer une modification

```bash
git add .
git commit -m "Description de la modification"
git push
```
