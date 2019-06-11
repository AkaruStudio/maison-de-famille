# GET /api/pages/buy

> Page acheter

```js
{
  header: {
    images: [
      {
        sources: [__image__, __image_en_webp__],
        alt: 'une maison'
      }
    ],
    title: 'Des biens immobiliers de prestige',
    subtitle: 'Paris ouest & sud'
  },
  advisorslink: {
    title: 'Nos conseillers ont une réelle expertise de leur quartier',
    text: 'Maisons de Famille Immobilier, ce n’est pas deux hommes mais toute une équipe. Chaque conseiller a une réelle expertise de son quartier. Il saura répondre à vos attentes en vous accompagnant tout le long de votre projet. N’hésitez pas à nous contacter pour organiser une première rencontre et nous faire part de votre projet. ',
    link: {
      to: '/conseillers',
      title: 'Voir nos conseillers',
      text: 'Voir nos conseillers'
    },
    image: {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }
  },
  cities: {
    title: 'Quelques photos sur le Chesnay',
    items: [{
      title: 'Clamart',
      image: {
        sources: [__image__, __image_en_webp__],
        alt: 'le quartier'
      },
      link: {
        to: '__slug_de_la_ville__',
        title: 'Voir la ville Clamart'
      },
      facilities: [{
        text: 'A13 + A86',
        icon: 'highway'
      }, {
        text: 'Grands espaces verts',
        icon: 'tree'
      }, {
        text: 'Mal desservie',
        icon: 'subway'
      }]
    }]
  }
}
```
