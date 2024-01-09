#Login

```mermaid
flowchart
    S[Start] --> A;
    A(Enter your email) --> B{Existing User};
    B -->|No| C(Enter name);
    C --> D{Accept Conditions?}
    D -->|No| A
    D -->|Yes| E(Send email with magic link)
```
