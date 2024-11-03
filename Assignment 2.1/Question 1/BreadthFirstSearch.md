
::: mermaid
graph TD
    subgraph "Breadth First Search"
    S1[S:1]
    A1[A:2]
    M1[M:2]
    B1[B:3]
    C1[C:3]
    I1[I:3]
    D1[D:4]
    E1[E:4]
    J1[J:4]
    K1[K:5]
    L11[L:5]
    L21[L:6]
    M21[M:7]
    G1[G:8]

    S1 --> A1
    S1 --> M1
    A1 --> B1
    A1 --> C1
    A1 --> I1
    C1 --> D1
    C1 --> E1
    I1 --> J1
    J1 --> K1
    J1 --> L11
    K1 --> L21
    L21 --> M21
    M21 --> G1
    end

:::