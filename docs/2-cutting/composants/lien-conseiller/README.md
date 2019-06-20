# Lien vers un/les conseiller(s)

---

![Image](./advisor.png)

## Propriétés

---

|nom|type|requis|default|description| 
|---|---|---|---|---|
title|Chaîne de caractères|oui|""|Le titre
text|Chaîne de caractères|oui|""|Le texte
link|Objet avec `to` et `title`|non|null|Le lien à afficher
image|[Image](/2-cutting/composants/image)|oui|null|L'image à afficher

## Composants

---

- [Image](/2-cutting/composants/image)

## API

---

```js
{
  title: 'Nos conseillers ont une réelle expertise de leur quartier',
  text: 'Maisons de Famille Immobilier, ce n’est pas deux hommes mais toute une équipe. Chaque conseiller a une réelle expertise de son quartier. Il saura répondre à vos attentes en vous accompagnant tout le long de votre projet. N’hésitez pas à nous contacter pour organiser une première rencontre et nous faire part de votre projet. ',
  link: {
    to: '/conseillers',
    title: 'Voir nos conseillers',
    text: 'Voir nos conseillers'
  },
  image: {
    // Voir composant Image 
    sources: [__image__, __image_en_webp__],
    alt: 'nos conseillers'
  }
}
```
