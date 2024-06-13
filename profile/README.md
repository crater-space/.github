# Crater

```mermaid
  flowchart TD
    M[fa:fa-computer User's Machine] <-->|Command Scripts| S
    S[fa:fa-code Service] <--> |Queries| R
    R[fa:fa-filter DB Reader] <--> |Info on Sources and Packages| D[fa:fa-database DB]
```
