# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
    => useState
    
- les composants enfants et les _props_ qu'on leur passe ✔️
    => hydratation des composants
    
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
    => event watching (onClick, onChange, onSubmit...)
    
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️
    => useEffect
    
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌

## 💻 J'utilise

### Un exemple personnel commenté ✔️

const [skills, setSkills] = useState<ISkillProps[]>([]);

const fetchSkills = async () => {
  const skillsData = await axios.get("http://localhost:5000/api/skill");
  setSkills(skillsData.data);
};

useEffect(() => {
  fetchSkills();
}, []);

Ce code récupère des données depuis une API REST, attend que le composant soit monté et stock les données reçus dans le state.

### Utilisation dans un projet ✔️

https://github.com/bapHyv/wild-book

Description : Exercice fait pendant les deux première semaine à la WCS formation DWWMA-CDA

### Utilisation en production si applicable ❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

https://beta.reactjs.org/

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
