
```mermaid
sequenceDiagram
    participant selain
    participant palvelin

    selain-->>palvelin: https://studies.cs.helsinki.fi/exampleapp/notes
    palvelin-->>selain: HTML dokumentti

    selain-->>palvelin: https://studies.cs.helsinki.fi/exampleapp/main.css
    palvelin-->>selain: CSS dokumentti

    selain-->>palvelin: https://studies.cs.helsinki.fi/exampleapp/main.js
     palvelin-->>selain: JavaScript dokumentti
```



