```mermaid
graph TD;
    A[Put sample in section] --> B[Dip in xylene for 3min];
    B --> C[Transfer to xylene for 2min];
    C --> D[Transfer to alcohol for 2min];
    subgraph First Phase
    D --> E[80% alcohol for 2min];
    E --> F[Methylated spirits for 1min];
    end
    F --> G[Under running water until not coloured];
    G --> H[Transfer to haematoxylin for 5min];
    subgraph Second Phase
    H --> I[Dip in acid alcohol 3-4 times];
    I --> J[Under tap water for 30sec-1min];
    end
    J --> K[Scotts tap water substitute for 1min];
    K --> L[Tap water for 30sec-1min];
    subgraph Third Phase
    L --> M[Eosin for 5min];
    M --> N[Tap water for 30sec-1min];
    end
    N --> O[Methylated spirits for 1min];
    O --> P[75% ethanol for 2min];
    subgraph Fourth Phase
    P --> Q[95% ethanol for 2min];
    Q --> R[100% ethanol for 2min];
    end
    R --> S[100% xylene for 2min];
    S --> T[100% xylene for 2min];

```
