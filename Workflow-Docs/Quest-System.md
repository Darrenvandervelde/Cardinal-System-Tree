## Quest System

```mermaid
flowchart LR
    A[Quest Start]
    B[Accept Quest]
    C[Objectives]
    D{Objective Complete?}
    E[Continue Objectives]
    F[Quest Complete]
    G[Rewards]

    A --> B
    B --> C
    C --> D
    D -- No --> E
    E --> C
    D -- Yes --> F
    F --> G
```
