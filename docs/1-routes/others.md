# GET /api/pages/agencies

> La page du comparatif d'autres agences

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
    title: 'Comparatif avec d\'autres types d\'agences'
  },
  blocks: [{
    type: 'table',
    datas: {
      datas: [{
        type: 'Services',
        items: [{
          name: 'estimation gratuite',
          classic: true,
          luxe: true,
          mdf: true
        }, {
          name: 'Un conseiller dédié au secteur',
          classic: true,
          luxe: false,
          mdf: true
        }]
      }, {
        type: 'Mise en valeur',
        items: [{
          name: 'Diagnostiques techniques',
          classic: true,
          luxe: true,
          mdf: true
        }, {
          name: 'Vidéos par drone',
          classic: false,
          luxe: false,
          mdf: true
        }]
      }]
    }
  }]
}


```
