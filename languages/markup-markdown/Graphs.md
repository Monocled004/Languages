# Mermaid
Used for adding Graphs & Charts in Markdown pages

```mermaid
flowchart LR;
    A(Start) -->|Transition comment| B[poawshviu];
    B --> C{Let me think};
    C -->|One| D[Laptop];
    C -->|Two| E[iPhone];
    C -->|Three| F[fa:fa-car Car];
```

1. __Flow Charts:__
   - Flowcharts are composed of nodes (geometric shapes) and edges (arrows or lines).
   - creating nodes:
     - default:
       ```
       ```mermaid
           flowchart LR;
               id;

     - Node with Text:
       ```
       ```mermaid
           flowchart LR;
               id1[This is the Text]
