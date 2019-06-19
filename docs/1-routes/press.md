# GET /api/pages/press

> La page des articles de presse

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
    title: 'Ils parlent de nous'
  },
  blocks: [{
    type: 'testimonial-list',
    datas: {
      text: 'Les témoignages de nos clients sont très important pour nous. C’est pour cette raison que lors de nos ventes, nous aimons récolter leurs avis, en voici quelques-uns.',
      testimonials: [{
        type: 'quote',
        image: {
          alt: 'mon alt',
          base: {
            source: 'monimagedefault.jpg'
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
          sources: [{
            source: '/uploads/home/testimonial0.jpg',
            width: 350
          }],
          alt: 'la vidéo de daniel'
        },
        author: 'Daniel t.',
        quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
      }, {
        type: 'quote',
        image: {
          alt: 'mon alt',
          base: {
            source: 'monimagedefault.jpg'
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
            source: 'monimagedefault.jpg'
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
      title: 'Nos biens de prestiges récents'
    }
  }, {
    type: 'cities-list',
    datas: {
      title: 'Nos villes & quartiers'
    }
  }]
}

```
