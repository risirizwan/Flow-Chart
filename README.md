```mermaid
flowchart TD
A[Project ABC]
...
```


A --> B[01_Archived]
A --> C[02_Published]
A --> D[03_Shared]
A --> E[04_Work in Progress]

%% Archived
B --> B1[Architecture]
B --> B2[Structure]
B --> B3[MEP]

%% Published
C --> C1[Architecture]
C --> C2[Structure]
C --> C3[MEP]

%% Shared
D --> D1[Architecture]
D --> D2[Structure]
D --> D3[MEP]

%% WIP
E --> E1[Architecture]
E --> E2[Structure]
E --> E3[MEP]

%% Common Folder Structure
B1 --> F[00 Model]
B1 --> G[10 Drawings]
B1 --> H[20 Details]
B1 --> I[30 Schedules]

B2 --> F
B2 --> G
B2 --> H
B2 --> I

B3 --> F
B3 --> G
B3 --> H
B3 --> I

C1 --> F
C1 --> G
C1 --> H
C1 --> I

C2 --> F
C2 --> G
C2 --> H
C2 --> I

C3 --> F
C3 --> G
C3 --> H
C3 --> I

D1 --> F
D1 --> G
D1 --> H
D1 --> I

D2 --> F
D2 --> G
D2 --> H
D2 --> I

D3 --> F
D3 --> G
D3 --> H
D3 --> I

E1 --> F
E1 --> G
E1 --> H
E1 --> I

E2 --> F
E2 --> G
E2 --> H
E2 --> I

E3 --> F
E3 --> G
E3 --> H
E3 --> I
