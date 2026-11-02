# Quiz Marvel

**Thème :** l'univers Marvel (héros, méchants et films)

**Projet :** AdaQuiz

**Membres du binôme :**
- Boukhari MFOIHAYA
- Edwin AMBROISINE

## Lancer le quiz

1. Récupère le dépôt :
   ```
   git clone https://github.com/[utilisateur]/[nom-du-depot].git
   ```
2. Va dans le dossier :
   ```
   cd [nom-du-depot]
   ```
3. Ouvre le fichier `index.html` 

4. Clique sur **Commencer** et joue.

## Ajouter une question

Seul le fichier `questions.js` est à modifier, pas `script.js`.

Ajoute un objet à la fin du tableau `questions` :

```js
{
  question: "Quel est le vrai nom de Hulk ?",
  reponses: ["Peter Parker", "Tony Stark", "Bruce Banner", "Steve Rogers"],
  bonne_reponse: 2
}
```

- `question` : l'énoncé.
- `reponses` : la liste des réponses possibles.
- `bonne_reponse` : l'**indice** de la bonne réponse dans la liste, en commençant à **0**.

## Ce que nous ferions avec une semaine de plus

- Mélanger l'ordre des questions et des réponses à chaque partie.
- Afficher une courte explication après chaque réponse.
- Récapituler à la fin les questions ratées avec leur bonne réponse.
- Ajouter un minuteur par question.
- Proposer plusieurs niveaux de difficulté ou plusieurs catégories (films, héros, méchants).
