# POST /api/pages/buy/slug

> Page détail d'un bien

```js
{
  name: 'Grande maison de maître',
  slug: 'grande-maison-de-maitre',
  city: 'Le chesnay',
  district: 'Centre',
  price: 810000,
  coord: {
    lat: 2.40,
    lng: 48.8534
  },
  publicationDate: 1000,
  benefits: [],
  area: 10,
  rooms: 5,
  bedrooms: 2,
  images: [{
    sources: ['/uploads/possessions/possession1-thumbnail.jpg'],
    alt: 'une maison'
  }],
  advisorslink: {
    title: 'Notre spécialiste Eric Flavioni nous parle de cette maison',
    text: 'J’aime particulièrement cette maison qui a un charme fou de par son histoire ! Elle appartenait au Duc de Champagne, c’est ici qu’il venait passé ses vacances. Ses hauts plafonds, ses    moulures sont typiques de l’époque. Son très grand salon ouvre sur un jardin remplis d’arbres centenaire !',
    link: {
      to: '/conseiller/eric',
      title: '',
      text: 'Voir nos conseillers'
    },
    image: {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }
  },
  similars: [],
  content: [{
    title: 'Description',
    content: 'À deux pas de la place du Châtelain, ensemble immobilier absolument exceptionnel aménagé par l\'architecte Andrée Putman avec art et qualité au départ du bâtiment qui servait d\'écurie aux chevaux de la compagnie des trams. Surface totale bâtie ± 2.600 m², surface terrain de ± 29 ares. Façade ± 60 mètres. Le bien est composé de 4 ailes s\'articulant autour d\'une vaste cour patio. Piscine intérieure, conciergerie. Surface bâtie au sol ± 1.482 m². Garage 5/6 voitures + 6 parkings protégés.'
  }, {
    title: 'Toutes les photos',
    images: [{
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }, {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }, {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }, {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }, {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }, {
      sources: [__image__, __image_en_webp__],
      alt: 'nos conseillers'
    }]
  }]
}
```
