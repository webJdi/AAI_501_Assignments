:::mermaid

graph TD
    subgraph "Depth First Search"
    S2[S:1]
    A2[A:2]
    M2[M:14]
    B2[B:3]
    C2[C:4]
    I2[I:7]
    D2[D:5]
    E2[E:6]
    J2[J:8]
    K2[K:9]
    L12[L:10]
    L22[L:11]
    M22[M:12]
    G2[G:13]

    S2 --> A2
    S2 --> M2
    A2 --> B2
    A2 --> C2
    A2 --> I2
    C2 --> D2
    C2 --> E2
    I2 --> J2
    J2 --> K2
    J2 --> L12
    L12 --> L22
    L22 --> M22
    M22 --> G2
    end

:::
