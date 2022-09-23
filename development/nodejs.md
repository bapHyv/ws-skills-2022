# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple) ✔️
    => npm i nodemon
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ✔️
    => Développer le composant d'accès aux données (Ex: DataSource avec typeorm)
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ❌
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

async function read(req: Request, res: Response): Promise<void> {
  try {
    const data = await DataSource.getRepository(Wilders).find({
      relations: {
        skillsToWildersRates: {
          skills: true,
        },
      },
    });
    res.send(formatedData);
  } catch (error) {
    console.log(error);
    res.status(500).send("Error while reading wilders");
  }
}
  
  Cette fonction est la callback qui est exécuté lorsque la route http://localhost:5000/api/wilder est appelé. Elle renvoie toutes les occurences de la table Wilders

### Utilisation dans un projet ✔️

https://github.com/bapHyv/backend-wild-book

Description :

### Utilisation en production si applicable ❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

  https://nodejs.org/en/docs/
  https://expressjs.com/fr/guide/routing.html
  https://typeorm.io/

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
