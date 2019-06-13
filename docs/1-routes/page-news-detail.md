# GET /api/pages/news/slug

> La news suivant le slug

```js
{
  header: {
    images: [{
      sources: [{
        source: '/uploads/possessions/possession1-thumbnail.jpg',
        width: '350'
      }],
      alt: 'une maison',
      title: 'Comment bien estimer votre bien ?'
    }]
  },
  blocks: [{
    type: 'text',
    datas: {
      title: 'Etudes de marché',
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
  }]
}

```
