# Introduction

Chaque réponse de l'API doit être de la forme 

```js
{
  statusCode: 1, // 0 ou 1
  status: 'success', // success ou error
  message: '' // Si error,
  datas: {} // les données 
}
```
