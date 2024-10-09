# Korata Transport Services Process Flow
# Business Process Flow

```mermaid
graph TD
    A[Driver takes car from parked area] --> B[Driver picks up kids]
    B --> C[Driver drops off kids at school]
    C --> D[Driver starts accepting Uber trips]
    D -->|Passenger enters| E[Driver introduces self and shares employment details]
    E --> F{Rider left item?}
    F -- Yes --> G[Take item to head office]
    F -- No --> H[Driver continues trips]
    H --> I[Close to school knock-off, driver goes to respective schools]
    I --> J[Driver drops kids at home]
    J --> K{Learner with extra-curricular activity?}
    K -- Yes --> L[Arrange pickup with parent]
    K -- No --> M[Driver resumes trips]
    L --> N[Kid is taken home after activities]
    M --> O[Driver resumes trips]
    O --> P[Driver goes to assigned restaurants]
    P --> Q[Driver drops off workers at homes]
    Q --> R{Continue trips until 10pm?}
    R -- Yes --> S[Continue accepting trips]
    R -- No --> T[Driver returns car to parking area]
    T --> U[Lead driver takes workers home]
    U --> V[Lead driver returns car and requests a ride home]
    V --> W[Lead driver sends bi-weekly report on drivers and car conditions]

graph TD
    A[Driver accepts a cash trip] --> B[Driver completes trip]
    B --> C[Deposit cash within 2 hours]

graph TD
    A[Lead driver manages petrol account] --> B[Driver requests refill]
    B --> C[Driver sends receipt to lead driver]
    C --> D[Lead driver transfers money via e-wallet]
    D --> E[Driver pays for petrol refill]
    E --> F[Lead driver sends proof to company email]

