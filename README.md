# Portfolio de Jessica Guillesser

Site professionnel de Jessica Guillesser — Cheffe de projet ERP et transformation digitale.

## Publication (2 étapes)

1. **Settings → Pages → Build and deployment → Source : GitHub Actions.** Enregistrez si GitHub le demande.
2. Dans le dépôt, cliquez sur **Add file → Upload files**. Chargez à la racine le fichier `Portfolio_Jessica_GitHub_Seguro_Actualizado.zip` fourni dans la conversation, puis cliquez sur **Commit changes** sur `main`.

Le workflow `.github/workflows/deploy.yml` s'exécute automatiquement. Suivez l'onglet **Actions**. Lorsque le déploiement est terminé, la page est accessible à **https://jektatis.github.io/WEB/**.

**Sécurité :** le workflow vérifie la somme SHA-256 de l'archive et extrait uniquement les 12 fichiers publics. Les aperçus et les notes privées ne sont pas publiés. Le CV actualisé est conservé dans `site/content.js` : il contient les expériences GA Smart Building, Groupe Casino, Saint-Gobain et USOAM. Après le premier téléchargement du ZIP, chaque modification de ce fichier déclenche automatiquement un nouveau déploiement de GitHub Pages, sans recharger le ZIP. Si vous modifiez ultérieurement le ZIP, demandez aussi une mise à jour du hash dans le workflow ; autrement le déploiement échouera volontairement.

> Ce dépôt est public : évitez d'y placer des documents personnels ou des informations confidentielles concernant votre employeur.


## Actualisations professionnelles

Les dates et intitulés historiques proviennent du CV d'octobre 2024 transmis par Jessica. L'expérience plus récente chez GA Smart Building provient de ses indications. Le numéro de téléphone et l'adresse personnelle ne sont pas diffusés sur ce site public.
