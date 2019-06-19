# GET /api/pages/cities

> Liste des villes

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
    }],
    title: 'Découvrez nos villes en détail'
  },
  blocks: [{
    type: 'thumbnail-list',
    datas: {
      title: 'Nos villes et quartiers'
    }
  }, {
    type: 'map',
    datas: {
      title: 'Nos villes sur une map'
    }
  }, {
    type: 'advisor-link',
    datas: {
      title: 'Nos conseillers ont une réelle expertise de leur quartier',
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
  }]
}

```
