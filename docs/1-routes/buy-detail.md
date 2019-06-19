# GET /api/pages/buy/slug

> Page détail d'un bien

```js
{
  header: {
    images: [{
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
    }]
  },
  blocks: [{
    type: 'text',
    datas: {
      title: 'Description',
      content: '<p>test</p>'
    }
  }, {
    type: 'text',
    datas: {
      title: 'Equipements',
      content: '<p>test</p>'
    }
  }, {
    type: 'slider',
    datas: {
      images: [{
        sources: [{
          source: '/uploads/possessions/possession1-thumbnail.jpg',
          width: '350'
        }],
        alt: 'une maison',
        text: 'Exemple d\'ibook'
      }, {
        sources: [{
          source: '/uploads/possessions/possession1-thumbnail.jpg',
          width: '350'
        }],
        alt: 'une maison',
        text: 'Deuxième photo'
      }],
    }
  }, {
    type: 'map',
    datas: {
      title: 'L\'emplacement de la maison'
    }
  }, {
    type: 'advisor-link',
    datas: {
      title: 'Notre spécialiste Eric nous parle de cette maison',
      text: 'Maisons de Famille Immobilier, ce n’est pas deux hommes mais toute une équipe. Chaque conseiller a une réelle expertise de son quartier. Il saura répondre à vos attentes en vous accompagnant tout le long de votre projet. N’hésitez pas à nous contacter pour organiser une première rencontre et nous faire part de votre projet.',
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
      link: {
        to: 'conseillers',
        title: 'test',
        text: 'Voir nos conseillers'
      }
    }
  }, {
    type: 'thumbnail-list',
    datas: {
      title: 'd\'autres biens similaires'
    }
  }]
}

```
