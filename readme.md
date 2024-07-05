# Odmiana imion występujących w Polsce

## Źródło imion

Imiona najczęściej występujące w Polsce pochodzą z https://api.dane.gov.pl/. Z imion męskich i żeńskich wybrałem te, które w styczniu 2024 roku pojawiły się wśród osób żyjących 1000 i więcej razy.

## Odmiana

Odmiana przez przypadki pochodzi z https://odmiana.net/. Jeśli imię nie występowało na stronie to zostało pominięte w pliku JSON. Jeśli odmiana liczby mnogiej nie była dostępna, przypadki w `plural` będą pustymi obiektami.

## Struktura pliku JSON

```
[
  {
    name,
    singular: {
      nom: {
        description,
        value
      },
      gen: {
        description,
        value
      },
      dat: {
        description,
        value
      },
      acc: {
        description,
        value
      },
      inst: {
        description,
        value
      },
      loc: {
        description,
        value
      },
      voc: {
        description,
        value
      }
    },
    plural: {
      nom: {
        description,
        value
      },
      gen: {
        description,
        value
      },
      dat: {
        description,
        value
      },
      acc: {
        description,
        value
      },
      inst: {
        description,
        value
      },
      loc: {
        description,
        value
      },
      voc: {
        description,
        value
      }
    }  
  }
]
```
