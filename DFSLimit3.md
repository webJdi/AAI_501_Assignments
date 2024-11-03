:::mermaid

graph TD
    subgraph "Depth First Search (Limit=3)"
    S3[S:1]
    A3[A:2]
    M3[M:9]
    B3[B:3]
    C3[C:4]
    I3[I:7]
    D3[D:5]
    E3[E:6]
    J3[J:8]
    K3[K:not visited]
    L13[L:not visited]
    L23[L:not visited]
    M23[M:not visited]
    G3[G:not visited]

    S3 --> A3
    S3 --> M3
    A3 --> B3
    A3 --> C3
    A3 --> I3
    C3 --> D3
    C3 --> E3
    I3 --> J3
    J3 --> K3
    J3 --> L13
    K3 --> L23
    L23 --> M23
    M23 --> G3

    style K3 fill:#f0f0f0,stroke-dasharray: 5 5
    style L13 fill:#f0f0f0,stroke-dasharray: 5 5
    style L23 fill:#f0f0f0,stroke-dasharray: 5 5
    style M23 fill:#f0f0f0,stroke-dasharray: 5 5
    style G3 fill:#f0f0f0,stroke-dasharray: 5 5
    end

:::