# Navigation

---

![Image](./nav.png)


## Propriétés

---

|nom|type|requis|default|description| 
|---|---|---|---|---|
items|Tableau|oui|[]|Les entrées de la navigation


## Composants

---

## API

---

> /api/nav

```js
{
  items: [{
    text: 'Acheter',
    children: [{
      text: 'Rechercher',
      icon: 'search',
      link: {
        to: '/acheter',
        title: 'Rechercher'
      }
    }, {
      text: 'Découvrez nos villes',
      icon: 'city',
      link: {
        to: '/nos-villes',
        title: 'Découvrez nos villes'
      }
    }]
  }, {
    text: 'Vendre',
    children: [{
      text: 'Services',
      icon: 'services',
      link: {
        to: '/services',
        title: 'Rechercher'
      }
    }, {
      text: 'Estimations',
      icon: 'calendar',
      link: {
        to: '/estimations',
        title: 'Estimations'
      }
    }, {
      text: 'Nos biens vendus',
      icon: 'sell',
      link: {
        to: '/nos-biens-vendus',
        title: 'Nos biens vendus'
      }
    }]
  }, {
    text: 'À propos',
    children: [{
      text: 'Notre team',
      icon: 'team',
      link: {
        to: '/team',
        title: 'Notre team'
      }
    }, {
      text: 'Témoignages clients',
      icon: 'message',
      link: {
        to: '/temoignages',
        title: 'Témoignages clients'
      }
    }, {
      text: 'Ils parlent de nous',
      icon: 'press',
      link: {
        to: '/presse',
        title: 'Ils parlent de nous'
      }
    }, {
      text: 'Comparatif autres agences',
      icon: 'tablet',
      link: {
        to: '/comparatif',
        title: 'Comparatif autres agences'
      }
    }]
  }, {
    text: 'Contact',
    children: [{
      text: 'Contactez-nous',
      icon: 'mail',
      link: {
        to: '/contact',
        title: 'Contactez-nous'
      }
    }, {
      text: 'Nous recrutons',
      icon: 'contact',
      link: {
        to: '/recrutement',
        title: 'Nous recrutons'
      }
    }, {
      text: 'Honoraires & mentions légales',
      icon: 'legal',
      link: {
        to: '/mentions-legales',
        title: 'Honoraires & mentions légales'
      }
    }]
  }]
}

```
