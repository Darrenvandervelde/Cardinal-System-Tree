## Game Save Flow

```mermaid
sequenceDiagram
    participant Client
    participant GameServer
    participant Database

    Client->>GameServer: Player Progress Update
    GameServer->>Database: Save Character Data
    Database-->>GameServer: Save Successful
    GameServer-->>Client: Progress Synced
```