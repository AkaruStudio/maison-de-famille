# GET /api/pages/sold

> La page des biens vendus

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
    title: 'Nos biens déjà vendus'
  },
  blocks: [{
    type: 'thumbnail-list',
    datas: {}
  }, {
    type: 'map',
    datas: {
      title: 'Nos biens vendus sur une map'
    }
  }]
}


```
