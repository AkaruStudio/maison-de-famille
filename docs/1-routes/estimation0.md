# POST /api/estimation

> Route du formulaire pour estimer un bien

### Envoi

---

```js
{
  zip_code: '',
  surface: '',
  bedrooms: '',
  price: ''
}
```

### Retour OK

---

```js
{
  statusCode: 1,
  status: 'success',
  interested: 130
}
```

### Retour pas OK

---

```js
{
  statusCode: 0,
  status: 'error',
  errors: [{
    field: 'zip_code',
    message: 'Le code postal n\'est pas correcte'
  }]
}
```
