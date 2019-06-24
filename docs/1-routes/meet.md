# POST /api/meet

> Route du formulaire de prise de rendez-vous

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
  street: '',
  city: '',
  zip_code: '',
  date: '',
  day: '',
  hour: ''
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
