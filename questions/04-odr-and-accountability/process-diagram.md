# Process diagram for challenge 4

```mermaid
flowchart TD
    A[Citizen entry: voice or assisted intake] --> B[Officer: eligibility, identity, authority and safety]
    B --> C{Safe and consented virtual participation?}
    C -->|No| D[Stop online route: officer arranges protection and lawful alternative]
    C -->|Yes| E[Lawful notice and assisted audio mediation]
    E --> F{Agreement reached?}
    F -->|Yes| G[Lawful terms, required execution and certification]
    F -->|No| H[Prescribed reasoned failure report]
    G --> I[Restricted record, accessible copy and human follow-up]
    H --> I
    D --> I
```

## Diagram explanation

The officer controls the safety gate before online mediation. An unsafe channel leads to protection and a lawful alternative. A safe session produces either a properly executed, certified agreement or a failure report. Each route retains a protected record and a named follow-up officer.

Stopping the online route does not itself waive mandatory initiation or create a valid failure report. The officer applies the relevant procedure. The diagram is a simplified view of the [answer](answer.md).
