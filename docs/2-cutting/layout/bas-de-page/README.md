# Footer

---

![Image](./footer.png)


## Propriétés

---

|nom|type|requis|default|description| 
|---|---|---|---|---|
text  |  Chaîne de caractères  |  non  |  ""  |  Le texte affiché
items|Tableau|oui|[]|Les entrées de la navigation
subtitle|Chaîne de caractères|non|""|Le sous titre


## Composants

---

## API

---

> /api/footer

```js
{
  text: 'Maisons de Famille Immobilier, ce n’est pas deux hommes mais toute une équipe. Chaque conseiller a une réelle expertise de son quartier. Il saura répondre à vos attentes en vous accompagnant tout le long de votre projet.',
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
    }]
  }, {
    text: 'Infos',
    children: [{
      text: '01.20.20.20.20',
      link: {
        // Notez la propriété type pour cet élément
        type: 'tel',
        title: 'Appeler le 01.20.20.20.20'
        to: '01.20.20.20.20'
      }
    }, {
      text: 'contact@mdfimmo.com',
      link: {
        // Notez la propriété type pour cet élément
        type: 'mail',
        title: 'Envoyer un mail à contact@mdfimmo.com'
        to: 'contact@mdfimmo.com'
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
