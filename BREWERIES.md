# Breweries

## GET brewery

- `/brewery/:key`

Example:

- `/brewery/guinness`
- `/brewery/fullers`
- `/brewery/brooklyn`
- `/brewery/gmodelo`
- `/brewery/ottakringer`

Results:

```json
{
  "key":"ottakringer",
  "title":"Ottakringer Brauerei",
  "synonyms":null,
  "since":1838,
  "address":"1160 Wien // Ottakringer Platz 1",
  "web":"www.ottakringer.at",
  "prod":740000,
  "tags":[],
  "beers":[
    {"key":"ottakringerhelles","title":"Ottakringer Helles"},
    {"key":"ottakringergoldfasslspezial","title":"Ottakringer Gold Fassl Spezial"},
    {"key":"ottakringerpils","title":"Ottakringer (Gold Fassl) Pils"},
    {"key":"ottakringerpur","title":"Ottakringer (Gold Fassl) Pur {Bio}"},
    {"key":"ottakringerzwickl","title":"Ottakringer (Gold Fassl) Zwickl"},
    {"key":"ottakringerzwicklrot","title":"Ottakringer (Gold Fassl) Zwickl Rot"},
    {"key":"ottakringerdunkles","title":"Ottakringer (Gold Fassl) Dunkles"},
    {"key":"ottakringerbock","title":"Ottakringer (Gold Fassl) Bock"}],
  "country":{"key":"at","title":"Austria"}
}
```

## GET random brewery

- `/brewery/rand`

