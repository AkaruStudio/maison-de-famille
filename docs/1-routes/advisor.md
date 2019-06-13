# GET /api/pages/advisor/slug

> La page du conseiller suivant le slug

```js
 {
  header: {
    images: [{
      sources: [{
        source: '/uploads/possessions/possession1-thumbnail.jpg',
        width: '350'
      }],
      alt: 'une maison'
    }],
    title: 'Edouard Danvy spécialiste Haut-de-seine'
  },
  card: {
    title: 'Fiche contact',
    advisor: {
      tel: '06099221100',
      mail: 'edouard@maison.fr',
      instagram: 'edouard',
      facebook: 'edouard.danvy'
    }
  },
  blocks: [{
    type: 'text',
    datas: {
      title: 'Infos',
      content: '<p>Maisons de Famille Immobilier est un nouvel acteur de l’immobilier de luxe à Paris et en proche couronne ouest qui offre une gamme de services de qualité pour satisfaire une clientèle de prestige aussi bien française qu’internationale. Nous (Edouard & Louis) avons décidé de sortir des réseaux classiques d’agence pour créer Maisons de Famille Immobilier. Motivés par l’envie d’innover et de proposer une expérience client moderne et complète, nous souhaitons créer une équipe dynamique et soudée pour répondre à cette démarche.Nos collaborateurs sont le cœur de notre activité : c’est de leur réussite et de leur talent que dépend le succès de Maisons de Famille Immobilier sur les différents secteurs géographiques du groupe.Tout sera mis en place pour faciliter votre intégration et votre encadrement. Vous aurez également la possibilité d’évoluer selon vos envies et vos résultats.Rejoignez-nous dans nos locaux modernes et écolos à Boulogne-Billancourt, et participez au développement de notre start-up ambitieuse.</p>'
    }
  }, {
    type: 'text',
    datas: {
      title: 'Historique',
      content: '<p>Maisons de Famille Immobilier est un nouvel acteur de l’immobilier de luxe à Paris et en proche couronne ouest qui offre une gamme de services de qualité pour satisfaire une clientèle de prestige aussi bien française qu’internationale. Nous (Edouard & Louis) avons décidé de sortir des réseaux classiques d’agence pour créer Maisons de Famille Immobilier. Motivés par l’envie d’innover et de proposer une expérience client moderne et complète, nous souhaitons créer une équipe dynamique et soudée pour répondre à cette démarche.Nos collaborateurs sont le cœur de notre activité : c’est de leur réussite et de leur talent que dépend le succès de Maisons de Famille Immobilier sur les différents secteurs géographiques du groupe.Tout sera mis en place pour faciliter votre intégration et votre encadrement. Vous aurez également la possibilité d’évoluer selon vos envies et vos résultats.Rejoignez-nous dans nos locaux modernes et écolos à Boulogne-Billancourt, et participez au développement de notre start-up ambitieuse.</p>'
    }
  }, {
    type: 'testimonial-list',
    datas: {
      title: 'Quelques avis recueillis sur Edouard',
      text: 'Les témoignages de nos clients sont très important pour nous. C’est pour cette raison que lors de nos ventes, nous aimons récolter leurs avis, en voici quelques-uns.',
      testimonials: [{
        type: 'quote',
        image: {
          alt: 'mon alt',
          base: {
            src: 'monimagedefault.jpg'
          },
          jpg: [{
            source: 'monimage_350.jpg',
            width: 350
          }, {
            source: 'monimage_700.jpg',
            width: 700
          }, {
            source: 'monimage_1400.jpg',
            width: 1400
          }],
          webp: [{
            source: 'monimage_350.webp',
            width: 350
          }, {
            source: 'monimage_700.webp',
            width: 700
          }, {
            source: 'monimage_1400.webp',
            width: 1400
          }]
        },
        video: {
          sources: ['/uploads/home/testimonial.mp4'],
          alt: 'la vidéo de daniel'
        },
        author: 'Daniel t.',
        quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
      }, {
        type: 'quote',
        image: {
          alt: 'mon alt',
          base: {
            src: 'monimagedefault.jpg'
          },
          jpg: [{
            source: 'monimage_350.jpg',
            width: 350
          }, {
            source: 'monimage_700.jpg',
            width: 700
          }, {
            source: 'monimage_1400.jpg',
            width: 1400
          }],
          webp: [{
            source: 'monimage_350.webp',
            width: 350
          }, {
            source: 'monimage_700.webp',
            width: 700
          }, {
            source: 'monimage_1400.webp',
            width: 1400
          }]
        },
        author: 'Daniel B.',
        quote: 'Son service est très efficace , le suivie de dossier est constant , son expertise local est juste et cohérent.'
      }, {
        type: 'quote',
        image: {
          alt: 'mon alt',
          base: {
            src: 'monimagedefault.jpg'
          },
          jpg: [{
            source: 'monimage_350.jpg',
            width: 350
          }, {
            source: 'monimage_700.jpg',
            width: 700
          }, {
            source: 'monimage_1400.jpg',
            width: 1400
          }],
          webp: [{
            source: 'monimage_350.webp',
            width: 350
          }, {
            source: 'monimage_700.webp',
            width: 700
          }, {
            source: 'monimage_1400.webp',
            width: 1400
          }]
        },
        author: 'Daniel t.',
        quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
      }]
    }
  }, {
    type: 'thumbnail-list',
    datas: {
      title: 'Les biens gérés par Edouard'
    }
  }, {
    type: 'cities-list',
    datas: {
      title: 'Villes & quartiers d\'Edouard'
    }
  }]
}
```
