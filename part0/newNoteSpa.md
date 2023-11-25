# NEW NOTE CREATED SPA

```mermaid
sequenceDiagram

 participant browser
    participant server

    browser->>server: https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    server-->browser: Status 201
    Note right of browser: No Redirect, does not load page again preventDefault(e)

```
