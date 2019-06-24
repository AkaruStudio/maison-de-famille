# POST /api/contact

> Route du formulaire de contact

### Envoi

---

```js
{
  civility: '', // m ou mme
  firstname: '',
  name: '',
  email: '',
  mobile: '',
  tel: '',
  message: ''
}
```

### Retour OK

---

```js
{
  statusCode: 1,
  status: 'success',
  message: 'Message envoyé'
}
```

### Retour pas OK

---

```js
{
  statusCode: 0,
  status: 'error',
  errors: [{
    field: 'firstname',
    message: 'Le prénom n\'est pas correcte'
  }]
}
```
