## Crafting System

```mermaid
flowchart LR
    A[Gather Materials]
    B[Open Crafting Menu]
    C{Recipe Valid?}
    D[Craft Item]
    E[Add Item To Inventory]
    F[Error Message]

    A --> B
    B --> C
    C -- Yes --> D
    D --> E
    C -- No --> F
```

