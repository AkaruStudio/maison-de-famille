# GET /api/pages/home

> Page d'accueil

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
  internallinks: [{
    image: {
      sources: [__image__, __image_en_webp__],
      alt: 'une maison'
    },
    title: 'Je souhaite acheter',
    link: {
      to: '/achats',
      title: 'Voir les achats'
    }
  }, {
    image: {
      sources: [__image__, __image_en_webp__],
      alt: 'une maison'
    },
    title: 'Je souhaite vendre',
    link: {
      to: '/services',
      title: 'Voir les ventes'
    }
  }],
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
    title: 'Nos villes & quartiers',
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
    }],
    ...
  },
  quotes: {
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
  },
  sublink: {
    title: 'Nous apportons 5 services faisant la différence ',
    subtitle: 'VENDEZ VOTRE BIEN',
    link: {
      to: 'services',
      title: 'Voir nos services',
      text: 'Nos services en détail'
    },
    services: [
      'Un conseiller unique et qualifié',
      'La création d’un dossier complet l’eBook House',
      'Une mise en valeur de votre maison',
      'Une communication Multi-Supports',
      'Un Suivi et un Accompagnement complets'
    ]
  }
}
```
