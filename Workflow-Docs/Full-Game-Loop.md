## Full Game Loop

```mermaid
flowchart LR
    A[Login]
    B[Character Select]
    C[Enter World]
    D[Explore]
    E[Combat]
    F[Loot]
    G[Quests]
    H[Level Up]
    I[Crafting]
    J[Trading]
    K[Guild Activities]
    L[Logout]

    A --> B --> C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    J --> K
    K --> D
    D --> L
```