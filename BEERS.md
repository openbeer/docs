# Beers

## GET beer

- `/beer/:key`

Example:

- `/beer/guinness`
- `/beer/murphysred`
- `/beer/brooklynlager`
- `/beer/corona`
- `/beer/ottakringerhelles`

Results:

```json
{
  "key": "ottakringerhelles",
  "title": "Ottakringer Helles",
  "synonyms": null,
  "abv": "5.2",
  "srm": null,
  "og": "11.8",
  "tags": [ ],
  "brewery": {
    "key": "ottakringer",
    "title": "Ottakringer Brauerei"
  },
  "country": {
   "key": "at",
   "title": "Austria"
  }
}
```

## GET random beer

- `/beer/rand`

