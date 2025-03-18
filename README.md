# jigsaw

```mermaid
flowchart TD
    A("fab:fa-youtube Starter Guide") --> B("fab:fa-youtube Make Flowchart")
    B --> C("fa:fa-book-open Learn More")
    C --> n1[" "] & D{"Use the editor"} & n2["Many shapes"]
    D -- Build and Design --> E("fa:fa-shapes Visual Editor")
    E --> F("fa:fa-chevron-up Add node in toolbar")
    D -- Use AI --> G("fa:fa-comment-dots AI chat")
    G --> H("fa:fa-arrow-left Open AI in side menu")
    D -- Mermaid js --> I("fa:fa-code Text")
    I --> J("fa:fa-arrow-left Type Mermaid syntax")
    n3["This is sample label"]

    n1@{ icon: "fa:gem", pos: "b", h: 24}
    n2@{ shape: delay}
    n3@{ img: "https://static.mermaidchart.dev/whiteboard/default-image-shape.svg", h: 200, w: 200, pos: "b"}
    style E color:#FFFFFF, fill:#AA00FF, stroke:#AA00FF
    style G color:#FFFFFF, stroke:#00C853, fill:#00C853
    style I color:#FFFFFF, stroke:#2962FF, fill:#2962FF



```
