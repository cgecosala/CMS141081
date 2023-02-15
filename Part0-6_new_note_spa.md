```mermaid

sequenceDiagram

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: status code 201
    Note right of browser: Browser executes JavaScript event handler to render notes 
    deactivate server
```