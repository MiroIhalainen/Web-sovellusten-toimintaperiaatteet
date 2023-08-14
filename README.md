Käyttäjä luo uuden muistiinpanon:

```mermaid
graph TD;
  Käyttäjä-->Muistiinpano
  Muistiinpano-->Palvelin
  Palvelin-->Muistiinpano_käsitelty
  Muistiinpano_käsitelty-->Käyttäjä
```
