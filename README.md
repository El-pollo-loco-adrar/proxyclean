# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Mise en place du formulaire de contact

1. https://formspree.io/
2. Création du compte avec l'adresse contact@proxiclean-services.fr
3. Crée un "New Form" et appelle-le "Contact ProxiClean".
4. Formspree va te donner une URL qui ressemble à : https://formspree.io/f/xyza123.
5. Remplace simplement https://formspree.io/f/VOTRE_ID_ICI dans mon code par cette URL. LIGNE 25

## 👀 Mise en place du formulaire d'envoie de CV
1. Créer un compte sur https://forminit.com/ avec le mail contact@proxiclean-services.fr
2. Créer un formulaire avec le nom : Recrutement ProxiClean
3. Récupérer l'URL. Sur le fichier rejoindre.astro, le mettre ligne 29 à la place du action=""


## Lignes à modifier
1. astro.config.mjs : ligne 16: mettre le bon lien du site