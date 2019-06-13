# GET /api/pages/buy

> Page acheter

```js
{
  header: {
    images: [{
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
    }]
  },
  blocks: [{
    type: 'thumbnail-list',
    datas: {

    }
  }, {
    type: 'map',
    datas: {
      title: 'Nos biens sur une map'
    }
  }, {
    type: 'advisor-link',
    datas: {
      title: 'Nos conseillers ont une réelle expertise de leur quartier',
      text: 'Maisons de Famille Immobilier, ce n’est pas deux hommes mais toute une équipe. Chaque conseiller a une réelle expertise de son quartier. Il saura répondre à vos attentes en vous accompagnant tout le long de votre projet. N’hésitez pas à nous contacter pour organiser une première rencontre et nous faire part de votre projet.',
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
      link: {
        to: 'conseillers',
        title: 'test',
        text: 'Voir nos conseillers'
      }
    }
  }, {
    type: 'cities-list',
    datas: {
      title: 'Nos villes & quartiers',
      cities: [{
        title: 'Clamart',
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
  }]
}

```
