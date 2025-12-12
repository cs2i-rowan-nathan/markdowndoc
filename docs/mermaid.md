---
icon: lucide/clock-3
---

# Mermaid

You can easily insert diagrams that represent workflows and processes.

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```



!!! note

    To learn more, go to the offical [documentation](https://zensical.org/docs/authoring/diagrams/)
