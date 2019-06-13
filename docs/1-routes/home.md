# GET /api/pages/home

> Page d'accueil

```js
module.exports = {
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
    }],
    title: 'Des biens<br> immobiliers de prestige',
    subtitle: 'Paris ouest & sud'
  },
  blocks: [
    {
      type: 'internal-links',
      datas: {
        links:[{
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
          title: 'Je souhaite acheter',
          link: {
            to: 'acheter',
            title: ''
          }
        }, {
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
          title: 'Je souhaite vendre',
          link: {
            to: 'vendre',
            title: ''
          }
        }]
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
    }, {
      type: 'testimonial-list', 
      datas: {
        text: 'Les témoignages de nos clients sont très important pour nous. C’est pour cette raison que lors de nos ventes, nous aimons récolter leurs avis, en voici quelques-uns.',
        testimonials: [{
          type: 'quote',
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
          video: {
            sources: ['/uploads/home/testimonial.mp4'],
            alt: 'la vidéo de daniel'
          },
          author: 'Daniel t.',
          quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
        }, {
          type: 'quote',
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
          author: 'Daniel B.',
          quote: 'Son service est très efficace , le suivie de dossier est constant , son expertise local est juste et cohérent.'
        }, {
          type: 'quote',
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
          author: 'Daniel t.',
          quote: 'A priori non porté sur les agences immobilières, j\'ai été conquis par le professionnalisme et la disponibilité de l\'agence et plus particulièrement d\'un Conseiller en particulier, M. Danvy. Sans aucun regret.'
        }]
      }
    }, {
      type: 'sublink',
      datas: {
        title: 'Nous apportons 5 services faisant la différence ',
        subtitle: 'VENDEZ VOTRE BIEN',
        link: {
          to: 'services',
          title: 'Voir nos services',
          text: 'Nos services en détail'
        },
        services: [
          'Un conseiller unique et qualifié',
          'La création d’un dossier complet l’eBook House',
          'Une mise en valeur de votre maison',
          'Une communication Multi-Supports',
          'Un Suivi et un Accompagnement complets'
        ]
      }
    }
  ]
}

```
