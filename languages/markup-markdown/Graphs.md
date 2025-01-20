# Mermaid
Used for adding Graphs & Charts in Markdown pages

1. __Flow Charts:__
   - Flowcharts are composed of nodes (geometric shapes) and edges (arrows or lines).
   - 
```mermaid
---
title: Example Flowchart
---
flowchart LR;
    A(Start) -->|Transition comment| B[poawshviu];
    B --> C{If };
    C -->|One| D[Laptop];
    C -->|Two| E[iPhone];
    C -->|Three| F[fa:fa-car Car];
```
   - creating nodes:
     - default:
       ```
       ```mermaid
           flowchart LR;
               id;
       ```
     - Node with Text:
       ```
       ```mermaid
           flowchart LR;
               id1[This is the Text];
       ```

   - Adding Markdown Text in graphs:
     - Use double quotes and backticks "` text `" to enclose the markdown text.
       ```
       \```mermaid
       %%{init: {"flowchart": {"htmlLabels": false}} }%%;
       flowchart LR;
       markdown["`This **is** _Markdown_`"];
       newLines["`Line1
       Line 2
       Line 3`"];
       markdown --> newLines;
       ```
