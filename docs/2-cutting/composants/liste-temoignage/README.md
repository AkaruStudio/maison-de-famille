# Liste de témoignages

---

![Image](./list.png)

## Propriétés

---

|nom|type|requis|default|description| 
|---|---|---|---|---|
text|Chaîne de caractères|oui|"quote"|Le type de témoignage. `quote` ou `press`
quotes|Tableau de [Témoignages](/2-cutting/composants/temoignage/)|oui|[]|La liste de témoignages à afficher


## Composants

---

- [Témoignage](/2-cutting/composants/temoignage/)


## API

---

```js
{
  text: 'Les témoignages de nos clients sont très important pour nous. C’est pour cette raison que lors de nos ventes, nous aimons récolter leurs avis, en voici quelques-uns.',
  quotes: [{
    type: 'quote',
    images: {
      sources: [__image__, __image_en_webp__],
      alt: 'l\'auteur de la citation'
    },
    layout: 'left',
    author: 'Daniel t.',
    quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
  }, {
    type: 'quote',
    images: {
      sources: [__image__, __image_en_webp__],
      alt: 'l\'auteur de la citation'
    },
    layout: 'left',
    author: 'Daniel t.',
    quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
  }, 
  ...
  ]
}
```
