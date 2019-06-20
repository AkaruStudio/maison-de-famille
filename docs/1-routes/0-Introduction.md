# Introduction

Chaque réponse de l'API doit être de la forme 

```js
{
  statusCode: 1, // 0 ou 1
  status: 'success', // success ou error
  message: '' // Si error,
  datas: {} // les données définies dans les pages suivantes
}
```

Pour les images, on a ce format là


```js
{
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
}
```

Dans chaque réponse de page, il y a une clef `blocks` qui est un tableau de tous les contenus de la page. Chaque block à un `type` qui me permet de décider en front ce que j'affiche.
