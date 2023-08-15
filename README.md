Käyttäjä luo uuden muistiinpanon:

```mermaid
sequenceDiagram
    osallistuja selain
    osallistuja palvelin
    
    selain->>palvelin: hakee https://studies.cs.helsinki.fi/exampleapp/notes
    aktivoi palvelin
    palvelin-->>selain: HTML document
    deaktivoi palvelin
    
    selain->>palvelin: https://studies.cs.helsinki.fi/exampleapp/main.css
    aktivoi palvelin
    palvelin-->>selain: the css file
    deaktivoi palvelin
    
    selain->>palvelin: https://studies.cs.helsinki.fi/exampleapp/main.js
    aktivoi palvelin
    palvelin-->>selain: the JavaScript file
    deaktivoi palvelin
    
    Note right of browser: The browser starts executing the JavaScript code that fetches the JSON from the server
    
    selain->>palvelin: https://studies.cs.helsinki.fi/exampleapp/data.json
    aktivoi palvelin
    palvelin-->>selain: [{ "content": "HTML is easy", "date": "2023-1-1" }, ... ]
    deaktivoi palvelin
    Note right of browser: The browser executes the callback function that renders the notes 
```


```mermaid
graph TD;
  Käyttäjä-->
```
